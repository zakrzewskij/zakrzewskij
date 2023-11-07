### Cloud
| CLOUD_ID (PK) | CLOUD_NAME       | ICON_URL                                       |
|---------------|------------------|------------------------------------------------|
| 1             | Azure            | <img height="40" src="https://skillicons.dev/icons?i=azure" alt="Azure"> |

### Scripting
| SCRIPTING_ID (PK) | SCRIPTING_NAME   | ICON_URL                                          |
|-------------------|------------------|---------------------------------------------------|
| 1                 | Bash             | <img height="40" src="https://skillicons.dev/icons?i=bash" alt="Bash"> |
| 2                 | PowerShell       | <img height="40" src="https://skillicons.dev/icons?i=powershell" alt="PowerShell"> |

### VersionControl
| VC_ID (PK) | VC_NAME       | ICON_URL                                              |
|------------|---------------|-------------------------------------------------------|
| 1          | Git           | <img height="40" src="https://skillicons.dev/icons?i=git,github" alt="Git, GitHub"> |
| 2          | TortoiseGit    | <img height="40" src="https://devicon-website.vercel.app/api/tortoisegit/original.svg" alt="TortoiseGit"> |
| 3          | Subversion     | <img height="40" src="https://devicon-website.vercel.app/api/subversion/original.svg" alt="Subversion"> |

### Programming
| PROGRAMMING_ID (PK) | PROGRAMMING_NAME | ICON_URL                                               |
|--------------------|-------------------|--------------------------------------------------------|
| 1                  | Python            | <img height="40" src="https://skillicons.dev/icons?i=python" alt="Python"> |
| 2                  | R                 | <img height="40" src="https://skillicons.dev/icons?i=r" alt="R"> |
| 3                  | LaTeX             | <img height="40" src="https://skillicons.dev/icons?i=latex" alt="LaTeX"> |
| 4                  | Markdown          | <img height="40" src="https://devicon-website.vercel.app/api/markdown/original.svg?color=%23FFFFFF" alt="Markdown"> |

### Database
| DB_ID (PK) | DB_NAME              | ICON_URL                                                   |
|------------|----------------------|------------------------------------------------------------|
| 1          | Oracle               | <img height="40" src="https://user-images.githubusercontent.com/25181517/117208736-bdedc080-adf5-11eb-912f-61c7d43705f6.png" alt="Oracle"> |
| 2          | SQLite               | <img height="40" src="https://devicon-website.vercel.app/api/sqlite/original.svg" alt="SQLite"> |
| 3          | Microsoft SQL Server | <img height="40" src="https://devicon-website.vercel.app/api/microsoftsqlserver/plain-wordmark.svg?color=%23FF0000" alt="Microsoft SQL Server"> |

### Collaboration
| COLLAB_ID (PK) | COLLAB_NAME  | ICON_URL                                                   |
|----------------|--------------|------------------------------------------------------------|
| 1              | Confluence   | <img height="40" src="https://devicon-website.vercel.app/api/confluence/original.svg" alt="Confluence"> |
| 2              | Jira         | <img height="40" src="https://devicon-website.vercel.app/api/jira/original.svg" alt="Jira"> |

### DevelopmentTools
| DEVTOOLS_ID (PK) | DEVTOOLS_NAME | ICON_URL                                                  | PROGRAMMING_ID (FK) | DB_ID (FK) | COLLAB_ID (FK) | CLOUD_ID (FK) | SCRIPTING_ID (FK) | VC_ID (FK) |
|------------------|---------------|-----------------------------------------------------------|---------------------|------------|----------------|---------------|-------------------|------------|
| 1                | VSCode         | <img height="40" src="https://skillicons.dev/icons?i=vscode" alt="VSCode"> | 1                   | 2          | 1              | 1             | 1                 | 1          |
| 2                | RStudio        | <img height="40" src="https://devicon-website.vercel.app/api/rstudio/original.svg" alt="RStudio"> | 2                   | 2          | 1              |               | 2                 |            |
| 3                | PyCharm        | <img height="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" alt="PyCharm"> | 1                   | 3          | 2              |               | 3                 | 2          |

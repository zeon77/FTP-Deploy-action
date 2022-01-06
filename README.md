# FTP-Deploy-action

based on [SamKirkland/FTP-Deploy-Action](https://github.com/SamKirkland/FTP-Deploy-Action)

Automate deploying websites with FTP. On every push it will be automatically run a Github Action, which will syncronize all modified files and folders with the server.

## Configuration:

Add New repository secrets at repo/Settings/Secrets menu with the following secret names and the corresponding values:
- `ftp_server`
- `ftp_username`
- `ftp_password`
- `ftp_basefolder`

`ftp_server`, `ftp_username`, `ftp_password` are required.

`ftp_basefolder` can be modified as needed

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=0077b6">](https://github.com/SamKirkland/FTP-Deploy-Action)

# 自动登录脚本使用说明

> author: kalila-cc

## Windows

1. 将文件 `login.cmd` 置于桌面 (Desktop)，便于以后双击直接运行自动登录脚本
2. 右键点击文件 `login.cmd`，并点击 **编辑**，将文件内容中的 `<#card_id#>` 整体替换为**你的 6 位卡号**，`<#password#>` 整体替换为**你的统一认证登录密码** _(**注意**，是整体替换，`<#` 和 `#>` 也要包括在内)_，并通过 `Ctrl + S` 保存文件修改
3. 配置完成，以后在桌面双击 `login.cmd` 即可自动登录

## macOS

1. 将文件 `login.command` 置于桌面 (Desktop)，便于后续修改文件可执行权限，也便于以后双击直接运行自动登录脚本
2. 以 **文本编辑** 方式打开文件 `login.command`，将文件内容中的 `<#card_id#>` 整体替换为**你的 6 位卡号**，`<#password#>` 整体替换为**你的统一认证登录密码** _(**注意**，是整体替换，`<#` 和 `#>` 也要包括在内)_，并通过 `command + S` 保存文件修改
3. 修改 `login.command` 的可执行权限，在所有应用中搜索 `'terminal'` 会出现 **终端**，复制命令 `xattr -c ~/Desktop/login.command; chmod +x ~/Desktop/login.command`，打开终端后粘贴并回车执行命令
4. 配置完成，以后在桌面双击 `login.command` 即可自动登录，可以通过 `command + Q` 关闭命令行窗口

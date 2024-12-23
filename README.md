# 锤子便签（网页打包版，非官方！非官方！）

本项目利用 [Tauri](https://tauri.app/) 打包工具，将 [欢喜云](https://yun.smartisan.com/) 的网页版打包为桌面应用程序，理论上支持包括 MacOS、Windows 和 Linux 在内的所有平台。项目中所使用的资源均来源于网络，我不对任何使用本项目进行打包的行为负责，请确保仅用于非商业目的。

由于欢喜云的运营状况尚不明确，为避免服务中断导致数据丢失，请务必备份您的个人数据。

打包步骤：
1. 安装Rust开发环境
2. 安装tauri-cli打包工具：`cargo install tauri-cli --locked`
3. 在smartisan-note目录下运行：`cargo tauri build`

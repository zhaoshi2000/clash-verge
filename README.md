
<h1 align="center">
  < img src="./src/assets/image/logo.png" alt="Clash" width="128" />
  <br>
  Clash Verge
  <br>
</h1>

<h3 align="center">
基于tauri的图形用户界面。
</h3>

## 特性

- 完整支持 `clash` 配置，部分支持 `clash premium` 配置。
- 支持配置文件管理和增强（通过yaml和Javascript）。[文档](https://github.com/zzzgydi/clash-verge/wiki/%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)
- 简洁的用户界面，支持自定义主题颜色。
- 内置支持 [Clash.Meta](https://github.com/MetaCubeX/Clash.Meta) 核心。
- 系统代理设置和防护。

## 安装

从 [release](https://github.com/zzzgydi/clash-verge/releases) 下载。支持 Windows x64，Linux x86_64 和 macOS 11+

或者你可以自行构建。支持 Windows，Linux 和 macOS 10.15+

注意：如果在Windows上无法启动应用程序，请检查是否已安装 [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section)。

## 开发

你需要安装 Rust 和 Nodejs，查看[这里](https://tauri.app/v1/guides/getting-started/prerequisites)获取更多详细信息。然后安装 Nodejs 包。

```shell
yarn install
```

然后下载 `clash` 二进制文件... 或者你可以从 [clash premium release](https://github.com/Dreamacro/clash/releases/tag/premium) 下载并根据 [tauri config](https://tauri.studio/docs/api/config/#tauri.bundle.externalBin) 重命名。

```shell
yarn run check
```

然后运行

```shell
yarn dev
```

或者你可以构建它

```shell
yarn build
```

## 待办事项

> 这个坑有点大...

## 截图

<div align="center">
  < img src="./docs/demo1.png" alt="demo1" width="32%" />
  < img src="./docs/demo2.png" alt="demo2" width="32%" />
  < img src="./docs/demo3.png" alt="demo3" width="32%" />
  < img src="./docs/demo4.png" alt="demo4" width="32%" />
  < img src="./docs/demo5.png" alt="demo5" width="32%" />
  < img src="./docs/demo6.png" alt="demo6" width="32%" />
</div>

### 自定义主题

<div align="center">
  < img src="./docs/color1.png" alt="demo1" width="16%" />
  < img src="./docs/color2.png" alt="demo2" width="16%" />
  < img src="./docs/color3.png" alt="demo3" width="16%" />
  < img src="./docs/color4.png" alt="demo4" width="16%" />
  < img src="./docs/color5.png" alt="demo5" width="16%" />
  < img src="./docs/color6.png" alt="demo6" width="16%" />
</div>

## 声明

这是一个用于Rust练习的学习项目。

## 贡献

欢迎提Issue和PR！

## 致谢

Clash Verge基于或受到以下项目的启发：

- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): 使用Web前端构建更小、更快、更安全的桌面应用程序。
- [Dreamacro/clash](https://github.com/Dreamacro/clash): 一个基于规则的Go语言隧道。
- [MetaCubeX/Clash.Meta](https://github.com/MetaCubeX/Clash.Meta): 一个基于规则的Go语言隧道。
- [Fndroid/clash_for_windows_pkg](https://github.com/Fndroid/clash_for_windows_pkg): 基于Clash的Windows/macOS图形用户界面。
- [vitejs/vite](https://github.com/vitejs/vite): 下一代前端工具。速度快！

## 许可证

GPL-3.0 许可证。详细信息请参见[此处的许可证](./LICENSE)。
```

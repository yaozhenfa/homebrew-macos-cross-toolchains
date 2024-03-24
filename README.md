# macos-cross-toolchains

> 🚀 基于[messense](https://github.com/messense)开发交叉编译根据自己需要升级了对应glibc 2.8版本后版本，目前只支持intel芯片的MAC。

手动下载预编译好的交叉工具链 [GitHub Release](https://github.com/yaozhenfa/homebrew-macos-cross-toolchains/releases)

建议采用Homebrew安装，使用下载的包启动会出现未信任的开发者。

```bash
brew tap yaozhenfa/macos-cross-toolchains
brew install yaozhenfa/homebrew-macos-cross-toolchains/x86_64-unknown-linux-gnu
brew install yaozhenfa/homebrew-macos-cross-toolchains/aarch64-unknown-linux-gnu
```

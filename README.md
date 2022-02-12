## Intro

你可以在 [Oracle 官网](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)下载不同版本、适用于不同平台的JDK安装包。

但是，你必须要先使用一个Oracle的账号登录(在我大三的时候还不需要这一步)。

我不想每次下载都登录`avoid login everytime, before i need to download it`。

我只想下载一次，然后把文件存起来。

`Download once, save it. Then do not need download it everytime`.

以后每次要重新安装配置，使用已经下载好的文件即可。


所以把文件存储在这里，希望可以省去大家的下载步骤。


## Usage

文件上传用到了 git LFS(Large File Storage)

但是对于文件的下载，则简单许多。

1. `git clone https://github.com/wuyujin1997/jdk-download-windows-linux-macos.git`

  then you can use JDK file at you local machine.

2. click download link at any browser.

## huaweiyun

感谢华为云提供的文件服务：
你可以在以下两个页面中找到你需要的JDK下载链接：

<https://repo.huaweicloud.com/java/jdk/>
<https://repo.huaweicloud.com/openjdk/>

- JDK 8

```shell
wget -c https://repo.huaweicloud.com/java/jdk/8u181-b13/jdk-8u181-windows-x64.exe

wget -c https://repo.huaweicloud.com/java/jdk/8u181-b13/jdk-8u181-macosx-x64.dmg

wget -c https://repo.huaweicloud.com/java/jdk/8u181-b13/jdk-8u181-linux-x64.tar.gz
```

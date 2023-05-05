# atk-imx6ull-openwrt
基于正点原子imx6ull阿尔法开发板移植openwrt

编译环境：Ubuntu20.04

开发板：核心板V1.6 底板V2.2

openwrt版本：18.06，linux内核版本：同正点原子提供的4.1.15

编译前准备：
sudo apt-get install build-essential subversion git-core libncurses5-dev zlib1g-dev gawk flex quilt libssl-dev xsltproc libxml-parser-perl mercurial bzr ecj cvs unzip python3-distutils

更新软件包：./scripts/feeds update -a

安装软件包：./scripts/feeds install -a

编译：make V=s

目前仅支持sd卡启动

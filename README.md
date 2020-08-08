# HLAE-Archieve
This repo automatically stores hlae_xxxxx.zip files when hlae has a new release, which could enable jsdelivr to speed up downloading.
> 该仓库存放hlae的压缩包，用于部分地区的加速下载

# Try this
https://cdn.jsdelivr.net/gh/Purple-CSGO/HLAE-Archieve@v2.103.1/v2.103.1/hlae_2_103_1.zip
> 试试这个，是不是秒速下载？

# API

官方仓库 Offical Repo

https://api.github.com/repos/advancedfx/advancedfx/releases

本仓库 This Repo

https://github.com/Purple-CSGO/HLAE-Archieve/blob/master/settings.json

```
{
	...
	"Files":["...", "..."]
}
```

或者

https://cdn.jsdelivr.net/gh/Purple-CSGO/HLAE-Archieve@v2.103.1/settings.json

# How to help us archieve

2. Create a repo on GitHub.
3. open `./settings.json `. Change `ThisOwner:"→Here←"` and `ThisRepo:"→Here←"` to your GitHub name and repo name.
4.  open `./github/workflows/transport.yml` . Change Line28 to your Repo.
5. Push this Directory to this repo.
6. Make a release using tag `v0.0.1`.

![](https://gitee.com/Purple-CSGO/Purp1e-Image-Hosting/raw/master/20200808083415.png)






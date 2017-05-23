# tumblr-source-list

一个简单的Tumblr资源工具，用于获取指定用户的图片或视频信息

### 使用方法

```
git clone https://github.com/seanhuai/tumblr-source-list
```

将本仓库Clone到本地后，修改app.py文件

如需获取指定用户的图片信息，请参考注释，调取tumblr_pics()函数，获取视频，调取tumblr_video()函数

```
tumblr_video('offo',40)
```


以上函数均接受两个参数，首个参数是用户二级域名，如offo.tumblr.com，则用户名是offo

第二个参数是获取数，一般填写20的倍数

生成的列表文件是用户同名文本文档，请使用下载工具完成下载
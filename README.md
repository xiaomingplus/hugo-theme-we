# We

We是一款基于[hugo](http://hugo.spf13.com)的中文主题,简约而优雅,单栏,适合技术与写作类博客.

![We screenshot](https://github.com/xiaomingplus/hugo-theme-we/blob/master/images/screenshot.png)

## 优点

* 简约出屎了,没有任何杂质
* 支持Disqus评论
* 支持分类/标签
* 支持分页
* 支持自定义导航

## 如何安装呢?

    git submodule add https://github.com/xiaomingplus/hugo-theme-we.git themes/we
    
然后编辑你的配置文件:

- `config.toml`

    ``` toml
    theme = "we"
    ```

- `config.yaml`

    ``` yaml
    theme: "we"
    ```

给你一个we主题示例的配置文件吧:

	baseurl = "http://localhost:1313/"
	title = "We"
	Paginate = 20
	theme= "we"
	hasCJKLanguage = true
	[[menu.main]]
	    name = "关于我"
	    identifier = "about"
	    url = "/about"
	[params]
	  disqusShortname = "spf13"


### 关于Disqus配置

在配置文件中添加你的disqus的shortname就行.

**TOML**
```toml
[params]
  disqusShortname = "spf13"
```

**YAML**
```yaml
params:
  disqusShortname: "spf13"
```


## License

拿去用,拿去改呗,但是得感谢下我.


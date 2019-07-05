# gitbook_mystyle
gitbook 书使用
[命令行工具,详情请看](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)

### 特别注意
不要执行 gitbook install  我改写了gitbook-plugin-splitter插件

### 运行步骤
```
安装命令行工具@2.3.2
npm install gitbook-cli -g
```

```
初始化工程
gitbook init
```

```
安装book.json中的插件
gitbook install
```

```
启动服务
gitbook serve
```

```
生成html 输出在_book目录下
gitbook build

```

### 编写说明

* markdownpad2-setup.exe markdown编辑工具
* 书的目录在 SUMMARY.md
* 全局样式在 styles/website.css
* 图片在 images目录中
* 内容区域的图片路径都用 /path/to/image.x格式，gitbook会转化为相对于html的相对路径
* README.md文件必须要有，不能删除
* SUMMARY.md中README.md必须加进来，不然会在目录第一行自动加introduction导航链向README.md
* 书名在 book.json 的insert-logo中配置
* 配置文件 book.json

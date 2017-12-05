# golang-review
golang review

vim ~/.bash_profile

GOPATH=/Users/changetheworld/go
export GOPATH

source ~/.bash_profile

$GOROOT

Golang常用框架

WEB框架
Gin:https://github.com/gin-gonic/gin
Gin是一个golang的微框架，封装比较优雅，API友好，源码注释比较明确，已经发布了1.0版本。具有快速灵活，容错方便等特点。其实对于golang而言，web框架的依赖要远比Python，Java之类的要小。自身的net/http足够简单，性能也非常不错。框架更像是一些常用函数或者工具的集合。借助框架开发，不仅可以省去很多常用的封装带来的时间，也有助于团队的编码风格和形成规范。
beego:https://github.com/astaxie/beego
beego 是一个快速开发 Go 应用的 HTTP 框架，他可以用来快速开发 API、Web 及后端服务等各种应用，是一个 RESTful 的框架，主要设计灵感来源于 tornado、sinatra 和 flask 这三个框架，但是结合了 Go 本身的一些特性（interface、struct 嵌入等）而设计的一个框架。
martini:https://github.com/go-martini/martini
revel:https://github.com/revel/revel
echo:https://github.com/labstack/echo

爬虫
go_spider:https://github.com/hu17889/go_spider
colly:https://github.com/gocolly/colly
pholcus:https://github.com/henrylee2cn/pholcus

数据库
Mysql:https://github.com/go-sql-driver/mysql
Redis:https://github.com/garyburd/redigo
sqlite3:https://github.com/mattn/go-sqlite3

缓存
freecache:https://github.com/coocood/freecache

HTTP
fasthttp :https://github.com/valyala/fasthttp
比net/http快10倍
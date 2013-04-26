VerticleSearchEngine
====================
## 介绍
用'commits'记录毕设摸索的过程，“学术分享搜素引擎” <br />
更多介绍参见 http://blog.csdn.net/zbf8441372/article/details/8697956

## 相关工具
#### Scrapy: python爬虫
用于个性化定制网页爬取，以及通用性内容爬取 <br />
基于twisted异步网络框架，代码少，性能高 <br />

#### MongoDB：面向文档NoSQL
用于元数据存储，以及pdf文件存取 <br />
易用性最高的NoSQL，分布式，多分片，易扩展，我的场景下适合取代MySQL <br />

#### Apache Lucene/Solr：索引建立/查询服务
为数据建立索引并定制隔离的搜索服务 <br />
最主流的搜索引擎搭建工具，互相兼容并提供常规搜索功能 <br />

#### Apache Tika：内容提取工具
用于提取pdf文本内容 <br />
兼容Lucene的多功能文本提取工具，适应很多类型文件，使用方便 <br />

#### CAS：开源单点登录解决方案
企业级SSO解决方案<br />

#### 其他：
Struts2 + Jquery + Bootstrap + D3 <br />

## 功能
基于爬取的学术资源，提供搜索、推荐、可视化、分享四块。



# 2016.2.1-2016.2.7

## 本周学习内容

### 1.Drupal的流结构：
  Drupal包含以下5层结构，自顶向下的顺序为：
    5）Template
    4)  User Permissions
    3)  Blocks and Menus
    2)  Modules
    1)   Data
   按照个人的理解，在Drupal中数据流动的过程为：
    1）源Data被划分包装成各项到module中
    2）module被划分聚合成Blocks，由Menus进行索引
    3)根据User Permission决定用户可见的内容。
    4）将筛选得的内容套入Template(Theme)中。

### 2.Drupal的用户类型：
    ..*Computer User: 能够操作drupal所安装的计算机的用户，若是安装在远程服务器，则该用户的账户为服务器管理员的账户。
    ..*Database User: 有权限操作数据库的账户。
    ..*User/1：超级用户，是唯一的，拥有网站内的任意管理权限。
    ..*User/2: 一般注册用户，绑定到个人，根据不同类型有不同的权限。
    ..*User/0: 匿名用户（游客）。

### 3.Taxonomies
    Taxonomies模块内的基本单位是vocabulary，vocabulary内包含多个terms，举例：
    
    Vocabulary = Music
       Term = Classical
          Sub-term = Concertos
          Sub-term = Sonatas
          Sub-term = Symphonies
       Term = Jazz
          Sub-term = Swing
          Sub-term = Fusion

###  4.Theme
    ..*Theme是drupal的主题包，由.info文件，模板文件，template.php三部分组成。
    ..*.info 是主体注册文件，提供主题的基本信息，如主体名称，页面划分区域，包含的样式表文件和js脚本等。
    ..*模板文件：定义了页面框架，根据用户请求，找出相应的模板进行填充并返回给用户。
    ..*template.php 用于填充模板前对显示变量对最后的处理。

### 5.Web Audio（初开坑状态）
  是一个比较新的javascript API，可以对嵌入网页中的音频文件进行处理和分析

  [官方API文档](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)


## 本周所做的事
    
    1.drupal环境搭建
    2.了解drupal基本概念并阅读官方文档中的totorial部分
    3.阅读drupal Theming Guide，开始自行编写theme包
    4.了解Web Audio基本概念，阅读实例代码
    5.与队友讨论X project内容，准备开始学习React。

## 本周评价

    * 这周的状态并不怎么好，因为3号就开始去亲戚家暂住，在亲戚家里学习工作诸多不便。到了6号回到老家，没有网络环境，加上拜访亲戚，完全没法工作ORZ。。。。。下周开始会慢慢脱离过年DEBUFF，相信能够静心做好更多的事了(想快点回家宅着干活T_T)。

## 下周计划
 
    1.完成theme包的编写
    2.开始外包的工作
    3.阅读React官方文档
    4.学习Web Audio
    5.学习Gulp


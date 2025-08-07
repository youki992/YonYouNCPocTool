# 用友NC漏洞批量检测工具

<a href="https://github.com/youki992/YonYouNCPocTool"><img alt="Release" src="https://img.shields.io/badge/YonYouNCPocTool-1.0-ff69b4"></a>
<a href="https://github.com/youki992/YonYouNCPocTool"><img alt="LICENSE" src="https://img.shields.io/badge/LICENSE-GPL-important"></a>
![GitHub Repo stars](https://img.shields.io/github/stars/youki992/YonYouNCPocTool?color=success)
![GitHub forks](https://img.shields.io/github/forks/youki992/YonYouNCPocTool)
![GitHub all release](https://img.shields.io/github/downloads/youki992/YonYouNCPocTool/total?color=blueviolet)  

用友NC系列漏洞检测利用工具，支持批量检测（多POC、多目标）、展示对应漏洞POC（方便手工验证）、dnslog交互、结果导出、AI问答交互等

> 免责声明：此工具仅限于安全研究，用户承担因使用此工具而导致的所有法律和相关责任！作者不承担任何法律责任！

> 运行方法：java -jar jar包（编译环境为Java 1.8）

## 🕳️ 目前已集成
* NC-BshServlet RCE
* NC-NCFindWeb目录遍历
* NC-checkekey SQL注入
* NC-down SQL注入
* NC-saveXmlToFileServlet 任意文件上传
* NC-UserQueryServiceServlet 反序列化
* NC-accept.jsp 任意文件上传
* NC-word.docx 任意文件读取
* NC-FormItemServlet SQL注入
* NC-runStateServlet-proInsPk SQL注入
* NC-workflowImageServlet SQL注入
* NC-grouptemplet 文件上传
* NC-download 任意文件读取
* NC-saveImageServlet 文件上传
* NC-FormulaViewAction SQL 注入
* NC-bill SQL 注入
* NC-cartabletimeline SQL 注入
* NC-yerfile_down SQL注入
* NC-Cloud smartweb2.RPC.d XXE
* NC-Cloud soapFormat.ajax XXE
* NC-Cloud MonitorServlet 反序列化
* NC-Cloud uapjs JNDI注入RCE
* NC-Cloud importhttpscer 任意文件上传
* NC-Cloud uploadChunk 任意文件上传

## ✨ 功能
###  单目标/多目标批量检测
![](pics/44b2585d-351d-4f3f-a97f-99199b291ff9.png)

### 设置ceye外带检测域名/Kimi AI key
![](pics/ee482e5a-22c6-4a37-aa1b-3cf73ed494d6.png)

### 配置说明
![](pics/61036832-7e9d-40ea-9711-5b55e25e4c05.png)

### 结果导出
![](pics/3c83c514-e58d-4150-a864-18e8fc380b8a.png)
![](pics/7124049f-d464-496e-923c-bd5ff6fb4d26.png)

## 🎯 后续更新
* 添加更多的POC
* 优化检测规则
* 优化POC显示

## ✅ 注意
* 本工具反序列化使用ysoserial-all.jar生成cc6利用poc，会在工具本地目录生成payload.bin文件
* 师傅们可以关注公众号，获取工具更新的第一手消息

## 交流
![](pics/gzh.png)

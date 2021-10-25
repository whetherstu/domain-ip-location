# domain-ip-location
#### 主要实现内容如下：
- 根据url提炼出对应的域名domain
- 根据域名找到对应的ip
	- 用 命令交互式 命令为nslookup
- 根据IP地址定位国家一节城市
	- 使用的是mmdb现有的离线对应数据库进行检索并且输出

#ip签名图
生成带来访者的地理位置(基于IP)，IP，系统版本，浏览器版本的图片。
<h2>效果如下(此处可能会显示Github的IP)<h2>
<img src="https://mp.wututu.cn/">
<h2>更新demo</h2>
<h2>主要修改部分</h2>
1:更换了IP的查询接口，新接口为<a href="https://api.ip.sb/geoip/" target="_blank">https://api.ip.sb/geoip/</a>，此接口支持识别IPV6地址的地理位置，但返回值为英文(例如ChinaJiangsuNanjing)</br>
2:增加了对使用Cloudflare站点的支持(在index.php中uncommit对应参数)</br>
3我们在beta版修改了api并删除了统计信息

# Apple Music 新加坡区专用分流规则
起因：因为找遍全网都没找到好用的，于是自己抓域名做了一个......\
初衷：大多数geosite和分流规则都只针对 Apple 自家的域名做，而对 Apple Music中的广播系列（包括本地电台、Apple Music 1 和 BBC 等国际电台）没有做分流。\
且根据观察，很多域名已经被弃用和换新。但大多数网站没有根据变动对上述域名及时更新，导致 Apple Music 使用体验不佳，难以满足本人的使用需求。\
AM在中国大陆有CDN，可以直接访问，畅通无阻，本项目也会将其标注以便于直连，避不必要的网络流量浪费。\
优点：本项目皆在抓出 Apple Music 使用的所有域名，该代理的代理，该直连的直连。在保证体验的前提下减少不必要的网络流量消耗。\
# 使用方法
direct.txt中的域名直连。proxy.txt中的域名代理，建议使用 DOMAIN-SUFFIX 进行匹配，举个例子

```bash
 - DOMAIN-SUFFIX,radio-activity.itunes.apple.com,PROXY
```

有什么不能用的欢迎提交issue......本人乃 Apple Music 重度用户，且认为新加坡区是最好用

#各种IOS Android Scheme intent  觉得密密麻麻点击右上角RAW
iOS 系统内置 URL Schema

单独说明做任务URLschemes  

Safari:       com.apple.mobilesafari

打开 Safari 浏览器 x-web-search://

小红书urlschemes

xhsdiscover://video_feed/id           ’,//视频作品页

xhsdiscover://item/id?type=normal     ’, //文字作品页

xhsdiscover://item/id?type=video      ’,//视频作品页

xhsdiscover://user/6704334291         , //用户主页

抖音urlschemes  火山urlschemes  极速urlschemes  多闪urlschemes   除了火山其他三个APP urlschemes只用改前缀  抖音Scheme  多闪 snssdk1349 极速版 snssdk2329 
火山关注页面

snssdk1112://profile?auto_follow=1&encryptedID=MS4wLjABAAAAkR1b_wEekr77jlFNTsjvQJOnyzkaYVmbwN_tj8e4-bw

火山作品页面 

snssdk1112://item?id=6622594672759934222

抖音/极速/多闪

跳转主页并关注: snssdk1128://user/profile/72673737181?refer=web&gd_label=click_wap_download_follow&type=need_follow&needlaunchlog=1

打开视频： snssdk1128://aweme/detail/6683443624597916941?refer=web&gd_label=click_wap_profile_feature&appParam=&needlaunchlog=1


国际版/国内版/国内绿色版

哔哩哔哩关注

bilibili://space/233134186

哔哩哔哩点赞

bilibili://video/559789678

哔哩哔哩关注+点赞(短视频页面)

bilibili://video/603471827?page=0&-Arouter=story&source=web




小红书Scheme
xhsdiscover://account/bind/’,//账号与安全

xhsdiscover://choose_share_user’,//分享给用户

xhsdiscover://dark_mode_setting/’,//深色设置

xhsdiscover://video_feed/id’,//视频作品页

xhsdiscover://general_setting/’,//通用设置

xhsdiscover://hey_home_feed/’,//记录我的日常

xhsdiscover://hey_post/’,//发布语音

xhsdiscover://home’,//主页

xhsdiscover://home/explore’,//发现列表

xhsdiscover://home/follow’,//关注列表

xhsdiscover://home/localfeed’,//同城列表

xhsdiscover://home/note’,//关注列表

xhsdiscover://home/store’,//商城

xhsdiscover://instore_search/result’,//商品搜索

xhsdiscover://instore_search/result?keyword=’,//商品搜索关键词

xhsdiscover://item/id’, //文字作品页

xhsdiscover://item/id?type=normal’, //文字作品页

xhsdiscover://item/id?type=video’,//视频作品页

xhsdiscover://search/result?keyword=’,//搜索关键词

xhsdiscover://me/profile’,//编辑资料

xhsdiscover://message/collections’,//收到的赞和收藏

xhsdiscover://message/comments’,//收到的评论和@

xhsdiscover://message/followers’,//新增关注

xhsdiscover://message/notifications’,//系统通知

xhsdiscover://message/strangers/’,//陌生人消息

xhsdiscover://messages’,//消息

xhsdiscover://notification_setting/’,//通知设置

xhsdiscover://post’,//发布作品-相册

xhsdiscover://post_note’,//发布笔记

xhsdiscover://post_video’,//发布视频

xhsdiscover://post_video_album’,//发布视频-全部相册

xhsdiscover://profile’,//我的个人页面

xhsdiscover://instore_search/recommend’,//商品搜索

xhsdiscover://recommend/contacts’,//通讯录好友

xhsdiscover://recommend/user’,//推荐用户

xhsdiscover://search/result’,//搜索

xhsdiscover://store’,//商城

xhsdiscover://system_settings/’,//开发者模式,可以修改登陆账号

xhsdiscover://topic/v2/keyword’,//话题

xhsdiscover://user/6704334291, //用户主页

xhsdiscover://user/id/followers’,//TA的粉丝

国际版/国内版/国内绿色版
哔哩哔哩关注

bilibili://space/233134186

哔哩哔哩点赞

bilibili://video/559789678

哔哩哔哩关注+点赞

bilibili://video/603471827?page=0&-Arouter=story&source=web

抖音Scheme  多闪 snssdk1349 极速版 snssdk2329 

home: "snssdk1128://feed?refer=web&gd_label={{gd_label}}",

detail: "snssdk1128://aweme/detail/{{id}}?refer=web&gd_label={{gd_label}}&appParam={{appParam}}&needlaunchlog=1",

user: "snssdk1128://user/profile/{{uid}}?refer=web&gd_label={{gd_label}}&type={{type}}&needlaunchlog=1",

challenge: "snssdk1128://challenge/detail/{{id}}?refer=web",

music: "snssdk1128://music/detail/{{id}}?refer=web",

live: "snssdk1128://live?room_id={{room_id}}&user_id={{user_id}}&from=webview&refer=web",

webview: "snssdk1128://webview?url={{url}}&from=webview&refer=web",

webview_fullscreen: "snssdk1128://webview?url={{url}}&from=webview&hide_nav_bar=1&refer=web",

poidetail: "snssdk1128://poi/detail?id={{id}}&from=webview&refer=web",

forward: "snssdk1128://forward/detail/{{id}}",

billboard_word: "snssdk1128://search/trending",

billboard_video: "snssdk1128://search/trending?type=1",

billboard_music: "snssdk1128://search/trending?type=2",

billboard_positive: "snssdk1128://search/trending?type=3",

billboard_star: "snssdk1128://search/trending?type=4"

火山 snssdk1112

home: "snssdk1112://",

item: "snssdk1112://item?detail_label=return_page",

item_follow: "snssdk1112://item?auto_follow=1&detail_label=return_page",

profile: "snssdk1112://profile",

profile_follow: "snssdk1112://profile?auto_follow=1",

room: "snssdk1112://room",

webview: "snssdk1112://webview",

hash: "snssdk1112://hashtag_collection",

circle: "snssdk1112://moment_detail?media_type=5&show_moment_title=1&is_show_circle=1",

circle_hashtag: "snssdk1112://moment_feed"

火山关注
snssdk1112://profile?auto_follow=1&encryptedID=MS4wLjABAAAAkR1b_wEekr77jlFNTsjvQJOnyzkaYVmbwN_tj8e4-bw

火山作品页面 snssdk1112://item?id=6622594672759934222

抖音      
跳转主页并关注: snssdk1128://user/profile/72673737181?refer=web&gd_label=click_wap_download_follow&type=need_follow&needlaunchlog=1

打开视频： snssdk1128://aweme/detail/6683443624597916941?refer=web&gd_label=click_wap_profile_feature&appParam=&needlaunchlog=1

原声（同一个音乐的作品）： snssdk1128://music/detail/6680045787365247747?refer=web 

热搜榜： snssdk1128://search/trending

最热视频: snssdk1128://search/trending?type=1

音乐榜: snssdk1128://search/trending?type=2

热搜（正能量）: snssdk1128://search/trending?type=3

明星爱豆榜: snssdk1128://search/trending?type=4

抖音内打开网址: snssdk1128://webview?url=http%3A%2F%2Fbaidu.com&from=webview&refer=web

抖音内打开网址（全屏）: snssdk1128://webview?url=http%3A%2F%2Fbaidu.com&from=webview&hide_nav_bar=1&refer=web




IOS系统包名
Camera:       com.apple.camera

AppStore:     com.apple.AppStore

Contacts:     com.apple.MobileAddressBook

Mail:         com.apple.mobilemail

GameCenter:   com.apple.gamecenter

MobileSafari: com.apple.mobilesafari

Preferences:  com.apple.Preferences

iPod:         com.apple.mobileipod

Photos:       com.apple.mobileslideshow

Calendar:     com.apple.mobilecal

Clock:        com.apple.mobiletimer

Safari:       com.apple.mobilesafari


设置 perfs:root=ControlCenter&path=CUSTOMIZE_CONTROLS

关于本机 prefs:root=General&path=About

通用 prefs:root=General

邮件 prefs:root=ACCOUNT_SETTINGS

飞行模式 prefs:root=AIRPLANE_MODE

自动锁定时间修改页面 prefs:root=General&path=AUTOLOCK

自动锁定时间修改页面（和上面的功能一样） prefs:root=DISPLAY&path=AUTOLOCK

iOS 钱包 shoebox://url-scheme

电池用量 prefs:root=BATTERY_USAGE

蓝牙 prefs:root=Bluetooth

iCloud prefs:root=CASTLE

描述文件 prefs:root=General&path=ManagedConfigurationList

日期与时间修改 prefs:root=General&path=DATE_AND_TIME

Facetime通话设置 prefs:root=FACETIME

音乐设置 prefs:root=MUSIC

键盘设置 prefs:root=General&path=Keyboard

键盘设置-键盘 prefs:root=General&path=Keyboard/KEYBOARDS

语言与地区 prefs:root=General&path=INTERNATIONAL

定位服务 prefs:root=Privacy&path=LOCATION

蜂窝网络设置 prefs:root=MOBILE_DATA_SETTINGS_ID

备忘录设置 prefs:root=NOTES

通知设置 prefs:root=NOTIFICATIONS_ID

钱包与 Apple Pay prefs:root=PASSBOOK

电话设置 prefs:root=Phone

照片设置 prefs:root=Photos

隐私设置 Prefs:root=Privacy

还原 prefs:root=General&path=Reset

铃声设置 prefs:root=Sounds&path=Ringtone

Siri 设置 prefs:root=SIRI

壁纸设置 prefs:root=Wallpaper

无线局域网 WIFI 设置 prefs:root=WIFI

打开 Safari 浏览器 x-web-search://

备忘录 mobilenotes://

打开地图map: //

给某人发送短信：sms://手机号

打电话给某人 tel://13800138000

打开微信 weixin://

打开手机 QQ mqq://

微信扫一扫 weixin://scanqrcode

打开网易云音乐 orpheuswidget://

打开支付宝 alipay://

滴滴出行 diditaxi://

百度云网盘 baiduyun://

建设银行 wx2654d9155d70a468://

招商银行 cmbmobilebank://

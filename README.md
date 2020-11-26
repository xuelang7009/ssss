

## Script脚本列表

1.  京东水果([jd_fruit.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_fruit.js))
2.  东东萌宠([jd_pet.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_pet.js))
4.  种豆得豆([jd_plantBean.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_speed.js))
6.  摇钱树([jd_moneyTree.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_moneyTree.js))
6.  宠汪汪([jd_joy.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy.js))
7.  宠汪汪偷好友狗粮与积分([jd_joy_steal.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_steal.js))
8.  宠汪汪单独喂食([jd_joy_feedPets.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_feedPets.js))
9.  宠汪汪兑换奖品([jd_joy_reward.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_reward.js))
10.  宠汪汪强制为好友助力(刷好友)([jd_joy_help.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_help.js))
11.  宠汪汪赛跑助力([jd_joy_run.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_run.js))
12.  宠汪汪聚宝盆辅助脚本([jd_petTreasureBox.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_petTreasureBox.js))
13.  取关京东店铺和商品([jd_unsubscribe.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_unsubscribe.js))
14.  东东超市([jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js))
15.  东东超市兑换奖品([jd_blueCoin.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_blueCoin.js))
16.  进店领豆([jd_shop.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_shop.js))
17.  摇京豆([jd_club_lottery.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_club_lottery.js))
18.  全名开红包([jd_redPacket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_redPacket.js))
19.  京东多合一签到([jd_bean_sign.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_sign.js)) 【可N个京东账号，Node.js专用，核心脚本是JD_DailyBonus.js， IOS软件用户请使用NobyDa的 [JD_DailyBonus.js](https://raw.githubusercontent.com/NobyDa/Script/master/JD-DailyBonus/JD_DailyBonus.js) 】
20.  京豆变动通知([jd_bean_change.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_change.js))
21.  京喜工厂([jd_dreamFactory.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_dreamFactory.js))
22.  东东小窝([jd_small_home.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_small_home.js))
21.  以及其他一部分在特定时间可用的薅京豆脚本，如 [手机狂欢城](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_818.js) 、[星推官](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_xtg.js) 等。

**脚本兼容: [QuantumultX](https://apps.apple.com/us/app/quantumult-x/id1443988620), [Surge](https://apps.apple.com/us/app/surge-4/id1442620678), [Loon](https://apps.apple.com/us/app/loon/id1373567447), 小火箭, JSBox, Node.js**

**TODO**

- [x] 完善京小超脚本[jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js)
- [x] 京小超商圈助力功能[jd_superMarket.js](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js)

## 食用方法

### 方法一：本地安装Node.js，下载本库脚本

  - 教程请见：[EvineDeng/jd-base](https://github.com/EvineDeng/jd-base)，适用于以下系统：

    1. Armbian/OpenWrt/Debian/Ubuntu/CentOS/Fedora/RedHat等Linux系统

    2. Android

    3. MacOS

### 方法二：云服务器、腾讯云函数等等

  - 需自行有云服务器，云函数等
  - 腾讯云云函数 [快速部署教程](tencentscf.md)（免费）
  - 腾讯云云函数控制台使用 [教程说明](iCloud.md)
  - 腾讯云云函数 [GitHub Action部署教程](tencentscf.md#github-action-部署)
       
 
### 方法三：Docker（NAS或VPS用户）

 - 可以精确控制任务运行时间，有三种办法：[docker办法一](https://github.com/lxk0301/jd_scripts/tree/master/docker)、[docker办法二（和本地安装Node.js类似）](https://github.com/EvineDeng/jd-base)、[docker办法三](https://github.com/chinnkarahoi/jd-scripts-docker)
 - [环境变量](https://github.com/lxk0301/jd_scripts/blob/master/githubAction.md#%E4%B8%8B%E6%96%B9%E6%8F%90%E4%BE%9B%E4%BD%BF%E7%94%A8%E5%88%B0%E7%9A%84-secrets%E5%85%A8%E9%9B%86%E5%90%88)
 
#### 注：以上三种运行机制都是Node.js，故您需仔细阅读下面几点


  - 如果使用方法一与方法二，需自行提供京东cookie填写到 [jdCookie.js](https://github.com/lxk0301/jd_scripts/blob/master/jdCookie.js) 里面

   
  - 获取京东cookie教程可参考 [浏览器获取京东cookie教程](https://github.com/lxk0301/jd_scripts/blob/master/backUp/GetJdCookie.md) , [插件获取京东cookie教程](https://github.com/lxk0301/jd_scripts/blob/master/backUp/GetJdCookie2.md)

  - 方法三Docker安装Cookie请见各自的说明。

### 方法四：iOS系统的代理软件（QuantumultX, Surge, Loon, 小火箭）

#### 以下内容只针对iOS用户

#### ios使用多个京东账号，需要使用BoxJs保存多会话进行切换 

##### BoxJs简单说明可看作者[BoxJs仓库地址](https://github.com/chavyleung/scripts/)

使用box可以实现远程订阅助力好友(需订阅此 [链接](https://raw.githubusercontent.com/lxk0301/jd_scripts/master/lxk0301.boxjs.json))

- [BoxJs使用教程](https://chavyleung.gitbook.io/boxjs/)

- [BoxJs教程视频](https://youtu.be/eIpBrRxiy0w)


【用box订阅的好处】

 1、脚本也可以远程挂载。京东活动助力功能的分享码只需在box里面填写。以后只需远程更新就行。

 2、所有脚本的cookie都可以备份，方便你迁移到其他支持box的软件。

 3、box可以支持多账号

```
# QuantumultX

#东东农场
5 6-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdnc.png, enabled=true

#东东萌宠
15 6-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_pet.js, tag=东东萌宠, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdmc.png, enabled=true

# 种豆得豆
1 7-21/2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdzd.png, enabled=true

#天天加速
8 */3 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_speed.js, tag=京东天天加速, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdjs.png, enabled=true

#京东摇钱树
3 */2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_moneyTree.js, tag=京东摇钱树, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdyqs.png, enabled=true

#京东宠汪汪
15 */2 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy.js, tag=京东宠汪汪, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#宠汪汪偷好友积分与狗粮
0 0,6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_steal.js, tag=宠汪汪偷好友积分与狗粮, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#京东宠汪汪喂食
15 */1 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_feedPets.js, tag=京东宠汪汪喂食, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

#宠汪汪积分兑换奖品
0 0-16/8,12 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_reward.js, tag=宠汪汪积分兑换奖品, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true

# 宠汪汪邀请助力与赛跑助力
15 10 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_joy_run.js, tag=宠汪汪邀请助力与赛跑助力, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdcww.png, enabled=true
 
#京小超
11 1-23/5 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_superMarket.js, tag=京小超, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jxc.png, enabled=true

#京小超兑换奖品
0 0 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_blueCoin.js, tag=京小超兑换奖品, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jxc.png, enabled=true

#进店领豆
10 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_shop.js, tag=进店领豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jd_shop.png, enabled=true

#摇京豆
5 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_club_lottery.js, tag=摇京豆, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jdyjd.png, enabled=true

#京东全民开红包
1 1 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_redPacket.js, tag=京东全民开红包, img-url=https://raw.githubusercontent.com/58xinian/icon/master/jd_redPacket.png, enabled=true

#京豆变动通知
2 9 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_bean_change.js, tag=京豆变动通知, enabled=true

#京东手机狂欢城
1 0-18/6 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_818.js, tag=京东手机狂欢城, enabled=true

#京东星推官
2 0 * * * https://raw.githubusercontent.com/lxk0301/jd_scripts/master/jd_xtg.js, tag=京东星推官, enabled=true
```


# ShoppingMiao
购物喵秒杀、抢购、低价购等内容。用于京东、淘宝、天猫、小米有品、苏宁易购、考拉海购、唯品会等平台的秒杀、抢购、低价购等。<br>
根据对应电商规则更新。<br>
#### 本人话少，欢迎Star <br>
* 更新支持京东<br>
* 更新支持苏宁、考拉<br>
* 更新支持唯品会<br>
![wechat](https://www.qxn110.com/wp-content/uploads/2020/02/me.jpg) <br>
Author:Reg_coco <br>
Wechat:yikunzhu<br>

### CENTOS:
yum install -y  python36 <br>
yum install -y python36-setuptools <br>
yum install -y python36-pip <br>
pip --default-timeout=100 install selenium #国内镜像：pip install --index https://mirrors.ustc.edu.cn/pypi/web/simple/  selenium <br>

### DEBIAN/UBUNTU:
sudo apt-get update <br>
sudo apt-get install python3.6 <br>
pip --default-timeout=100 install selenium #国内镜像：pip install --index https://mirrors.ustc.edu.cn/pypi/web/simple/  selenium <br>

### WINDOWS:
 安装python3 <br>
 安装pip <br>
 pip --default-timeout=100 install selenium #国内镜像：pip install --index https://mirrors.ustc.edu.cn/pypi/web/simple/  selenium <br>

## 使用说明：
1）适用于京东、淘宝、天猫、小米有品、苏宁易购、考拉海购等，其他平台可添加微信 yikunzhu 反馈后，继续增加。 <br>
2）必须配合chrome浏览器（71-73版本）使用 <br>
3）跳至商品页面请在开售时间前选择所有商品规格（如鞋码、配色） <br>
4) 扫码登陆后，chrome浏览器可能会拦截重定向请求，如发生请在浏览器地址栏末尾收到跳转网页。但不影响操作。 <br>
5) 提前设置默认邮寄地址和电话，中途无法更改 <br>
6) 无法在下单页面操作，不适用使用优惠券等情况 <br>
7) 开售后自动下单，在淘宝规定时间内完成支付<br>


淘宝、天猫、小米有品、苏宁易购、考拉海购平台运行：python shoppingmiao.py <br>
京东平台：python shoppingmiao_jd.py <br>
唯品会平台：python shoppingmiao_vip.py

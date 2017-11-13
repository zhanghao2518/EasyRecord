## 易记录
一款用于记录账户密码的app

UI及功能参照IOS应用:password 3
### 特点：
 1. 专门用于保存账号密码
 2. 无网络访问权限，仅本地保存，不能上传到任何服务器
 3. 数据库加密，使保存的信息更加安全
 4. 无广告，开源免费项目
 5. 有记录入侵功能，记录输入错误密码时，时间就、地点及拍照记录
 6. 遵循Google material design 设计风格
 
 #### 使用第三方框架:
 * 事件处理 Rxjava 2.0 
 * 权限管理 rxpermissions
 * UI事件处理 rxbinding2
 * 图片处理 glide3.8
 * 查找控件 butterknife
 * Recycleview列表优化 BaseRecyclerViewAdapterHelper
 * 数据库 greendao3.2
 * 数据库加密 net.zetetic:android-database-sqlcipher:3.5.7
 * 日志管理 logger
 * 设备数据查看 stetho
 * 策划删除 EasySwipeMenuLayout
 * 九宫格图片展示 ninegridview
 * 图片获取 takephoto_library
 * 内存泄漏查看 leakcanary

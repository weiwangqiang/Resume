 <center>
     <h1>韦王强</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             18852852276
         </span>
         |
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             WeiwqMr@outlook.com
         </span>
         |
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://weiwangqiang.github.io/">个人博客</a>
         </span>
         |
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="https://blog.csdn.net/to_perfect?type=blog">CSDN</a>
         </span>
          |
         <span>
          <img src="assets/graduation-cap-solid.svg" width="18px">
          本科
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男，1995 年出生
 - 求职意向：Android 研发工程师
 - 工作经验：5 年
 - 期望薪资：面谈
 - 教育经历：江苏大学，电子信息工程专业，18年本科毕业，获得CET6证书。

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 掌握Android常用组件、AIDL、自定义View，了解AMS，事件分发，ANR实现原理。
- 掌握Profile，Perfetto，Systrace，Leakcanary等分析工具，有性能优化经验。
- 掌握Lifecycle、ViewModel、LiveData、ViewBinding、DataBinding等Jetpack相关组件。
- 掌握MVP、MVVM、EventBus、ButterKnife、OkHttp、Retrofit、Glide等框架和开源库。
- 掌握Java常用集合、多线程、代理、注解、反射、泛型等。
- 掌握常用的数据结构和设计模式，了解TCP/IP，Http协议，会爬虫。
- 了解Python、C++、HTML、JS基本用法，了解Flutter基本开发。


## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **CVTE，TV 研发部门，Android 工程师，2018.07~至今**

   主要工作：负责 TV预装应用，如Settings、电视管家、引导应用、多媒体、FTV语音的研发和维护工作，处理应用国际化的需求。
   
   效率改善：开发在线签名网站，实现傻瓜式签名；扩展翻译库后端功能，实现翻译进度可视化。

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **FTV 语音**

  *Retrofit，Glide，WindowView，RecyclerView，ROOM，AudioRecord，SoundPool*

  描述：FTV语音是TV端的产品，包含远场唤醒、音乐影视的点播和控制，天气、股票、所见所喊、打开应用，闹钟，百科等功能。
  
  职责：
  
  - 独自负责TV端应用框架的搭建和一期的功能开发，以及扩展研究院关于TV前期的NLU、NLP技能。
  
  - 负责二期迭代的闹钟功能，包含闹钟设置、提醒、查看、删除。
  
  技术要点：
  
  - 使用自定义view实现炫酷的动画效果，通过WindowManager添加全局的bar条。
  - 使用profile 分析Java，native层内存分配，解决近10M的内存泄漏问题和启动异常。
  - 使用systrace分析App端链路耗时，按需解析json数据，降低58%的耗时。
  
  
  
- **Settings**

  *WifiManager，BluetoothAdapter*

  描述：包含网络配置，蓝牙，系统信息，系统OTA，时间等功能。
  
  职责：
  
  - 负责wifi和蓝牙关于Android版本的适配工作，系统OTA，时间等功能维护。
  
  - 开发有线网、wifi、蓝牙、系统信息等接口，作为SDK提供给AR眼镜使用。
  
  技术要点：
  
  - 查看Android Framework源码，适配Android 11的蓝牙功能
  - 通过Hook，代理技术，在不依赖系统接口的情况下，实现网络，蓝牙、系统信息接口的开发。
  
- **多媒体**

  *MediaPlay，Glide*

  描述：包含文件浏览，音视频的播放，高清图片播放，文件管理等。
  
  职责：负责多媒体音乐播放页面的开发，播放设置页面的维护工作。
  
  技术要点：
  
  - 通过MediaPlayer，service实现前后台音乐播放。
  
- **电视管家**

  *PMS*
  
  描述：包含内存优化、网络监控、启动控制、深度清理等。
  
  职责：负责电视管家的深度清理功能的开发，内存清理，应用自启动等功能的维护。
  
  技术要点：
  
  - 替换掉android.jar，来绕过PackageManager的接口限制，再通过PMS实现应用数据，垃圾的清理。
  
- **引导应用**

  *WifiManager，AIDL*

  描述：包含国家，语言，密码，网络等设置

  职责：负责密码设置、WIFI设置功能的开发，对语言、国家等设置功能的维护工作。

  技术要点：

  - 使用AIDL，与TV中间层进行跨进程通信
  - 使用dumpsys命令查看activity任务栈，解决应用无响应问题。

- **在线签名**

  *Python，Shell，Html*

  描述：在前端选择签名方案并提交Apk文件，即可获取到签名后的Apk。

  职责：负责开发前端和Python后端

  技术要点：

  - 前端通过监听用户鼠标，实现拖拽上传Apk
  - 后端使用Python搭建简易版本的服务器，通过Shell脚本执行Apk签名。

- **翻译库**

  *SpringBoot，MongoDB，Python爬虫*

  描述：翻译需求管理和进度的可视化

  职责：主要开发翻译需求的提交、估价、翻译回稿的逆向、导入翻译到mongoDB等相关接口。
  
  技术要点：
  
  - 使用Springboot搭建后端接口
  - MongoDb作为翻译数据库
  - 使用Python爬取Google，必应翻译接口，实现自动化批量翻译。

## 自我评价

- 具有良好的学习能力和求知欲，对于自己不熟悉的领域、技术栈，也能较快入手。
- 具有良好的独立思考和解决问题能力，善于总结和复盘。
- 具有良好的表达能力、团队意识。

## 致谢

感谢您花时间阅读我的简历，期待有机会能与您共事。

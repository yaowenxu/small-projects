## 北航网关 nodejs 脚本登录 BUAAGW-Autologin （Ubuntu 20.04平台）
- 主要思路：通过修改 gw.buaa.edu.cn js脚本，通过nodejs后台执行登录；
- 适用版本：SRun Auth Interface Server:SRunCGIAuthIntfSvr V1.18 B20190701
- 参考自：[https://github.com/jiegec/auth-tsinghua](https://github.com/jiegec/auth-tsinghua)
- 相关参考：
    - [https://github.com/YeC1213/Srun3kWebPortalLogin](https://github.com/YeC1213/Srun3kWebPortalLogin)
    - [https://github.com/huxiaofan1223/jxnu_srun](https://github.com/huxiaofan1223/jxnu_srun)
    - [https://github.com/z4yx/GoAuthing](https://github.com/z4yx/GoAuthing)
- 运行过程：
    - 运行 init.sh 初始化环境；
    - 修改 start.sh 中的用户名和密码，并运行！

### 运行结果
![Cron 运行结果](cron-log.png "Cron 运行结果")
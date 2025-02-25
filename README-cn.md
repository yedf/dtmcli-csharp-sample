[English](./README.md) | 简体中文

# dtmcli-csharp-sample
dtmcli c# 使用示例

**已废弃, 合并到了 [client-csharp/samples · dtm-labs/client-csharp](https://github.com/dtm-labs/client-csharp/tree/main/samples)**

# 快速开始

## 非 docker 用户

### 部署启动dtm

参考 [dtm安装运行](https://dtm.pub/guide/install.html)

### 运行示例
```
cd DtmSample
dotnet run DtmSample.csproj
```

这个时候通过浏览器打开 `http://localhost:9090` 会跳转到 swagger 页面，可以选择性的测试对应类型的事务模式。

> PS: 为了便于快速体验，示例代码中的数据库是可以直接使用的了。

## docker 用户
有两种方式快速运行示例代码：
1. 通过执行 `runsample.ps1` 来快速运行示例代码。
2. 打开Visual Studio，在工具栏选择`Docker Compose` 运行，该模式下可以进行端点调试。

以上两种方式会通过 **docker-compose** 启动 dtm，mysql(演示子事务屏障)，dtmsample。

启动后，可以看到类似下面的输出

![](./media/run.png)

同样的通过浏览器打开 `http://localhost:9090` 会跳转到 swagger 页面，可以选择性的测试对应类型的事务模式。

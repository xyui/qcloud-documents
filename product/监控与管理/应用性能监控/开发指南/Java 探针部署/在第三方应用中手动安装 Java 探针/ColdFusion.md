本文将为您介绍如何在 ColdFusion 上安装 Java 探针

### 在 ColdFusion 上安装 Java 探针

1. 访问 **ColdFusion Administrator Console** 。

2. 从左侧菜单依次选择： **SERVER SETTINGS -> Java and JVM**。

3. 在  **JVM Arguments**  输入框里，配置 `-javaagent` 参数。

   ```shell
   -javaagent:/${路径}/tapm-agent-java.jar
   ```

4. 点击 **Submit Changes**。

5. 重启 ColdFusion 。

> ?探针暂时不支持 ColdFusion Version 9 on IIS 。
# VstcCameraLib
威视达康摄像头API，官方提供的SDK只有demo，没有直接调用的API，这里进行了抽取封装。

### 接口功能 VstcApi
```java

	/**
	 * 扫描摄像头
	 * 注意：在子线程中调用
	 */
	public static void startSearch(final Context context, final OnSearchListener onSearchListener)
  
 
	/**
	 * 连接摄像头
	 * @param strDID 序列号
	 * @param devicePass 密码
	 * @param onConnectListener 回调
	 */
	public static void connectCamera(final String strDID, final String devicePass, final OnConnectListener onConnectListener)
  
```

### 使用实例
- 参考MainActivity代码
- [官方提供的开发文档](http://www.vstarcam.cn/channel-67.html?tdsourcetag=s_pcqq_aiomsg)

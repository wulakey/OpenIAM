#扫码登录
1.调用生成二维码接口，将随机用户标识包含在url中，形如: WEB@aef5f08daeff41b49b183a880f38d791
2.通过APP扫描解析出url，然后调用验证接口，传入随机用户标识，用户号进行绑定
3.WEB前端不断轮询查询随机用户标识是否验证通过，通过则生成cookie，保存获取的用户信息
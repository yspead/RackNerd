# 如何免费申请 Microsoft 365 E5 开发者订阅

任何人都可以注册成为 Microsoft 开发者，免费申请为期3个月的 Microsoft 365 E5 开发者订阅，理论上可以无限续订，从而一直免费使用 Microsoft 365。

## 更新日志

- **2021-10-12** 续订成功（第二次）
- **2021-07-14** 续订成功
- **2021-05-13** 本文发布（同时申请 Microsoft 365 E5 开发者订阅）

## 申请订阅

### Step 1：登录你的 Microsoft 个人账号

打开 [Microsoft 开发者页面](https://developer.microsoft.com/en-us/office/profile/)，登录你的 Microsoft 个人账号（如果没有，就注册一个 Microsoft 账号）。

![Microsoft 开发者登录页面](https://bbtdd.com/img/41054684037096.webp)

### Step 2：注册 Microsoft 开发者账号

依次填写你的个人信息，注册 Microsoft 开发者账号。

![加入 Microsoft 365 开发者计划](https://bbtdd.com/img/0963378493625.webp)

![填写个人信息](https://bbtdd.com/img/9241810991.webp)

![完成注册](https://bbtdd.com/img/05103931.webp)

### Step 3：申请 Microsoft 365 E5 订阅

点击“SET UP SUBSCRIPTION”，开始申请 Microsoft 365 E5 订阅。

![设置订阅](https://bbtdd.com/img/2782450562601.webp)

依次填写你的个人信息，注册 Microsoft 365 E5 的管理员账号。

![填写管理员信息](https://bbtdd.com/img/857811395474699.webp)

添加你的手机号码，然后点击“Send code"。填写收到的验证码之后，最后点击"Set up"。

![验证手机号码](https://bbtdd.com/img/31836023931854.webp)

## 订阅管理

### Step 1：登录你的 Microsoft 365 E5 的管理员账号

打开 [Microsoft 365 管理员中心](https://admin.microsoft.com/Adminportal/Home)，登录你的 Microsoft 365 E5 的管理员账号。

### Step 2：分配产品许可证

点击"添加用户"，注册一个 Microsoft 365 E5 的子账号。

![添加用户](https://bbtdd.com/img/6584966249231312.webp)

设置基本信息。

![设置基本信息](https://bbtdd.com/img/2744040998740113.webp)

分配产品许可证。

![分配产品许可证](https://bbtdd.com/img/52147189777.webp)

可选设置。

![可选设置](https://bbtdd.com/img/917313502825004.webp)

添加完毕。

![添加完毕](https://bbtdd.com/img/3752996770560045.webp)

![用户列表](https://bbtdd.com/img/8917712320.webp)

## 调整空间

用户默认的 OneDrive 存储空间为 1TB，如果你想调整特定用户的存储空间，可以参考 [这篇文章](https://docs.microsoft.com/zh-cn/onedrive/change-user-storage)。

## 自动续订

![续订成功](https://bbtdd.com/img/8452267326151737.webp)

自动续订是通过定期调用 Microsoft 365 E5 的 API 实现的，并不能保证 100% 续订成功（只能说大概率续订成功），因为存在人工审核的因素。

建议使用 API 挂载你的本地目录，只要里面的文件有更改，就会自动同步到 OneDrive 远程目录，从而实现文件备份。同时还调用 Microsoft 365 E5 的 API，就可以实现自动续订。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)
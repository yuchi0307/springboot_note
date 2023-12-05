# springboot筆記
<ul>
  <li>認識 Spring Boot </li>
  <li>深入瞭解Spring框架</li>
  <li>Spring 常用功能</li>
</ul>

# 認識 Spring Boot
Spring Boot 為 Spring 推出的新功能，將 Spring 框架零件所組成的成品直接啟用，更為簡易快速。
# 深入瞭解 Spring 框架 - IOC 控制反轉
將 Obj 的控制權交給外部個 Spring 容器來管理，優點為 
1. Loose coupling 讓 class 之間的關聯性降低
2. Lifecycle Management 生命週期管理
3. More testable 方便測試程式

我的翻譯：反轉術式，會產生容器(獄門疆)封印有術士的人，方便任意取用
# @Component
用法: 只能加在 class 上

用途: 將該 class 變成由 Spring 容器所管理的 object

p.s. 被 Spring 容器創建的 object 稱作 bean ，其名為 class name 的第一個字母轉小寫

![Hahow for Business06：44](https://github.com/yuchi0307/springboot_note/assets/67968321/f90f20a2-cb40-4242-a667-89b9e129c0c8)

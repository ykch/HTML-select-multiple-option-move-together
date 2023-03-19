# HTML-select-multiple-option-move-together
## You Can choose multiple option move together

![image](https://github.com/ykch/HTML-select-multiple-option-move-together/blob/main/LINE_P2021114_234136.gif)
![image](https://github.com/ykch/HTML-select-multiple-option-move-together/blob/main/LINE_P2021117_012946.gif)

# idea

將select選單，有選項目往上「↑」移動的寫法了  
  
假設項目有N個  
檢查N-1次(最後一個不檢查無條件移動)  
  
判斷方法每次都判斷：  
自己[0]  
下一個[1]  
  
當下一個[1]是被選擇時：(if)※出現bug補充條件自己[0]也(&&)不是被選時才可超越  
移動下一個[1]到最尾巴  
反向不是被選擇時：(else)  
移動自己[0]到最尾巴  
  
  
# References

參考資料  
HTML+JS实现左边select移动到右边select_勇勇米的博客-CSDN博客  
https://blog.csdn.net/weixin_41903771/article/details/83004130



參考資料  
支援將option排序到最前頭(首項)語法insertBefore與firstChild  
select - jQuery add blank option to top of list and make selected to existing dropdown - Stack Overflow  
https://stackoverflow.com/a/32741840

HTML DOM insertBefore() Method  
https://www.w3schools.com/Jsref/met_node_insertbefore.asp


readme gif - Google 搜尋  
在GitHub的README.md加入圖片及gif的方法. 1.點Upload files | by Steph Yang | Medium  
https://medium.com/@stephyang/在github的readme-md加入圖片及gif的方法-7282a4a63141


readme 換行 - Google 搜尋  
GitHub的README.md文件内容如何换行_md文件换行_马蹄印的博客-CSDN博客  
https://blog.csdn.net/bawcwchen/article/details/80557442

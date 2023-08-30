## Chapter 12: Columns
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 資源
https://github.com/gitdagray/css_course

### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept outline
###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Setup
        初始設定說明

###  4. Creating starting elements <Code更動>
        新增五個 p 元素
        前面四個 p 元素在 section 中，section 的 class selector 為 columns

###  5. Adding columns to a container element <Code更動>
        設定 section 元素的 class selector 為欄位數量為四欄。


###  6. Setting a column width <Code更動>
        設定欄位寬度為 250px ，並縮放觀察變化。

###  7. columns shorthand <Code更動>
        使用 columns 設定 欄位數量為四欄，
        欄位寬度為 250px

###  8. column-rule <Code更動>
        設定各欄間的分隔線條為 3px solid #333

###  9. column-gap <Code更動>
        設定各欄間的間隔為 3rem

### 10. Top margins and margin collapsing <Code更動>
        設定 margin-top 為 0，以消除邊界重疊。

### 11. Adding a header to the columns <Code更動>
        在 section 的段落中間，新增 h2
        設定 margin-top 為 0
        設定 背景為黑色，文字顏色為白色
        設定 padding 為 1rem

### 12. break-inside <Code更動>
        設定 break-inside 為 avoid

### 13. break-before <Code更動>
        設定 break-before 為 column
        使 Next Topic 的文字在最上方。

        縮放到最小會發生什麼問題?

### 14. column-span <Code更動>
        將 h2 元素改為 p 元素
        文字為 Where is my rug, man? The Dude
        class 為 quote

        前往 Unicode Character Table 網站
        找上引號代碼&#8220;、下引號代碼&#8221;並新增。
        找橫線代碼&#8212;並新增。

        設定文字大小 3rem ，文字置中，文字顏色為 #333，
        欄位間隔為 all。

### 15. Revisiting specificity <Code更動>
        (1)在 .quote 中，新增 margin-top 為 2rem，卻沒有變化。
        重新檢視 .columns p 和 .quote 的 specificity
        說明。
        (2)修改 pseudo 元素

### 16. Controlling line breaks with white-space <Code更動>
        不要使 The Dude 文字分開
        使用 span 元素，class 設定為 nowrap

        在 style.css 修改 white-space 為 nowrap

# LyXbookzh 说明

一个用来写中文书籍的LyX框架

### 主要文件

* main.lyx:  --- 主文件，从这里编译。 
* chapter*.lyx:  --- 各个章节。 
* appendix*.lyx:  --- 附录。 
* reference.bib:  --- bibtex格式文献数据库文件。 
* glossary.lyx:  --- 中英术语对照表。 
* nomenclature.lyx:  --- 符号系统。

### 在 LyX 中已经设置好的配置

在菜单Document->Settings处修改 
* Document class: ctex-book 
* Modules: Theorems(AMS, Numbered by Type) 
* Fonts: Use non-TeX fonts (via XeTeX/LuaTeX) 
* Page Layout: Two-sided document 
* Language: Chinese (simplified) 
    - Encoding: Unicode (utf8) 
* PDF Properties: Use Hyperref Support 
* Output:  
    - Default output format: PDF (XeTeX) 

### 关于参考文献的设置

使用bibtex。
encoding: utf8 (在File->Database Properties处修改)。


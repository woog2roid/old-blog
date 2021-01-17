---
title: "gitignore"

categories:
  - TIL
tags:
---
gitignore은 github나 git을 이용하면서 꼭 보게 되는 파일이다. VCS인 git에게 "이 파일은 관리하지 않아도 된다."라고 알려주는 용도이다. 사용방법도 간단해서, 그냥 .gitignore을 작성하고 git push를 해주면 적용이 된다.

# .gitignore 문법
|||  
|:---:|:---:|  
|#| #은 주석을 의미한다.|  
|*.a|확장자가 .a인 모든 파일을 무시한다.|  
|folder_name/|해당 폴더의 모든 파일을 무시한다.|  
|folder_name/*.a|해당 폴더의 확장자가 .a인 모든 파일을 무시한다.|  
|folder_name/**/*.a|해당 폴더를 포함한 하위 모든 폴더에서 .a인 모든 파일을 무시한다.|  
|/*.a|현재 폴더의 확장자가 .a인 모든 파일을 무시한다.|  
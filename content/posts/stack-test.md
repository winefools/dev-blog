+++
title = 'Stack Test'
date = 2025-08-13T17:40:17+09:00
draft = false
tags = ["devlog"]
categories = ["development"]
+++


ChatGPT의 말:

좋아요, 그럼 Stack 테마에서 바로 뜨는 포스트를 새로 만들어 보죠.
1. 포스트 생성

터미널에서:

cd ~/dev-blog
hugo new posts/stack-test.md

2. 파일 열기 & 내용 수정

content/posts/stack-test.md 열고 이렇게 수정하세요:

---
title: "Stack Theme Test Post"
date: 2025-08-13T19:00:00+09:00
draft: false
tags: ["devlog"]
categories: ["development"]
---

본문은 자유롭게 작성:

이건 Stack 테마에서 보이는 테스트 포스트입니다.

```bash
echo "Hello Stack!"


---

## 3. 서버 실행  
```bash
hugo server -t stack

    목록 페이지: http://localhost:1313/posts/

    글 페이지: http://localhost:1313/posts/stack-test/

📌 만약 여전히 안 뜬다면,

hugo server -t stack -D -F

로 실행해서 draft 글과 미래 날짜 글까지 포함해서 확인할 수 있습니다.

원하시면 제가 Stack 테마에 맞춰 자동 포스트 생성 템플릿을 만들어 드릴 수 있습니다.
그렇게 하면 다음부터는 hugo new posts/xxx.md 하면 바로 목록에 뜨게 됩니다.


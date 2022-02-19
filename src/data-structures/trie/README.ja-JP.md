# トライ

_他の言語で読む:_
[_简体中文_](README.zh-CN.md),
[_Русский_](README.ru-RU.md),
[_Português_](README.pt-BR.md),
[_日本語_](README.ja-JP.md)
コンピューターサイエンスでは、**トライ**はデジタルツリー、または基数ツリー、
プレフィックスツリー(プレフィックスで検索することが可能なため)とも呼ばれます。
検索木または順序木構造という動的セットや連想配列のようなキーがstringのものを格納するのに使われます。
バイナリ検索木とは違い、トライに格納されたノードにはそのノードに紐づくキーはありませんが、
その木の一そのものがそれに紐づくキーを定義しています。
ノードに紐づくすべての子ツリーはstringの共通プレフィックスを持っており、
そのルート(基)は空のstringが紐づいています。
しかし全てのノードに値が紐づいているとは限りません。むしろ、値は葉にのみ紐づいており、
その内部ノードは当該のキーと同様です。プレフィックス木の空間最適化の説明については、
コンパクトプレフィックス木をご参照ください。

![Trie](https://upload.wikimedia.org/wikipedia/commons/b/be/Trie_example.svg)

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Trie)
- [YouTube](https://www.youtube.com/watch?v=zIjfhVPRZCg&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8&index=7&t=0s)

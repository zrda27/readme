<h3>标题</h3>
<div class="image-package">
<img src="http://ww1.sinaimg.cn/large/6aee7dbbgw1effeaclhiyj20eh09cwez.jpg" alt="标题"><br><div class="image-caption">标题</div>
</div>
<p>标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 <code>#</code> 号即可。</p>
<p><code># 一级标题</code></p>
<p><code>## 二级标题</code></p>
<p><code>### 三级标题</code> </p>
<p>以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。</p>
<h3>列表</h3>
<p>熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 <code>-</code> 或 <code>*</code> 即可变为无序列表，有序列表则直接在文字前加<code>1.</code> <code>2.</code> <code>3.</code> 符号要和文字之间加上一个字符的空格。</p>
<div class="image-package">
<img src="http://ww4.sinaimg.cn/large/6aee7dbbgw1effew5aftij20d80bz3yw.jpg" alt="无序列表与有序列表"><br><div class="image-caption">无序列表与有序列表</div>
</div>
<h3>引用</h3>
<p>如果你需要引用一小段别处的句子，那么就要用引用的格式。</p>
<blockquote><p>例如这样</p></blockquote>
<p>只需要在文本前加入 <code>&gt;</code> 这种尖括号（大于号）即可</p>
<div class="image-package">
<img src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effezhonxlj20e009c3yu.jpg" alt="引用"><br><div class="image-caption">引用</div>
</div>
<h3>图片与链接</h3>
<p>插入链接与插入图片的语法很像，区别在一个 <code>!</code>号</p>
<p>图片为：<code>![](){ImgCap}{/ImgCap}</code></p>
<p>链接为：<code>[]()</code></p>
<p>插入图片的地址需要图床，这里推荐<a href="http://weibotuchuang.sinaapp.com" target="_blank">围脖图床修复计划</a> 与 <a href="http://www.getcloudapp.com" target="_blank">CloudApp</a> 的服务，生成URL地址即可。</p>
<div class="image-package">
<img src="http://ww2.sinaimg.cn/large/6aee7dbbgw1efffa67voyj20ix0ctq3n.jpg" alt="URL 与图片"><br><div class="image-caption">URL 与图片</div>
</div>
<h3>粗体与斜体</h3>
<p>Markdown 的粗体和斜体也非常简单，用两个 <code>*</code> 包含一段文本就是粗体的语法，用一个 <code>*</code> 包含一段文本就是斜体的语法。</p>
<p>例如：<strong>这里是粗体</strong> <em>这里是斜体</em> </p>
<h3>表格</h3>
<p>表格是我觉得 Markdown 比较累人的地方，例子如下：</p>
<pre><code>| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |</code></pre>
<p>这种语法生成的表格如下：</p>
<table>
<thead>
<tr>
<th>Tables</th>
<th style="text-align:center">Are</th>
<th style="text-align:right">Cool</th>
</tr>
</thead>
<tbody>
<tr>
<td>col 3 is</td>
<td style="text-align:center">right-aligned</td>
<td style="text-align:right">$1600</td>
</tr>
<tr>
<td>col 2 is</td>
<td style="text-align:center">centered</td>
<td style="text-align:right">$12</td>
</tr>
<tr>
<td>zebra stripes</td>
<td style="text-align:center">are neat</td>
<td style="text-align:right">$1</td>
</tr>
</tbody>
</table>
<h3>代码框</h3>
<p>如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来。图例：</p>
<div class="image-package">
<img src="http://ww3.sinaimg.cn/large/6aee7dbbgw1effg1lsa97j20lt0a8dgs.jpg" alt=""><br><div class="image-caption"></div>
</div>
<p>使用 <code>tab</code> 键即可缩进。</p>
<h3>分割线</h3>
<p>分割线的语法只需要三个 <code>*</code> 号，例如：</p>
<hr>
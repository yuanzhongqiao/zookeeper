# Apache ZooKeeper [![GitHub Actions CI][ciBadge]][ciLink] [![Travis CI][trBadge]][trLink] [![Maven Central][mcBadge]][mcLink] [![License][liBadge]][liLink]

<p align="left">
  <a href="https://zookeeper.apache.org/">
    <img src="https://zookeeper.apache.org/images/zookeeper_small.gif"" alt="https://zookeeper.apache.org/"><br/>
  </a>
</p>
<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-apache-zookeeper----" class="anchor" aria-hidden="true" tabindex="-1" href="#apache-zookeeper----"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Apache ZooKeeper </font></font><a href="https://github.com/apache/zookeeper/actions"><img src="https://github.com/apache/zookeeper/workflows/CI/badge.svg" alt="GitHub Actions CI" style="max-width: 100%;"></a> <a href="https://travis-ci.org/apache/zookeeper" rel="nofollow"><img src="https://camo.githubusercontent.com/4f63a1b79e7ef5e38bad676bb6595a9611e8b4f1f62e9ac6ec2e4f90edeae5f2/68747470733a2f2f7472617669732d63692e6f72672f6170616368652f7a6f6f6b65657065722e7376673f6272616e63683d6d6173746572" alt="特拉维斯·西尔" data-canonical-src="https://travis-ci.org/apache/zookeeper.svg?branch=master" style="max-width: 100%;"></a> <a href="https://zookeeper.apache.org/releases" rel="nofollow"><img src="https://camo.githubusercontent.com/ad83806860d4dee2b98109e99820feadefe1faec2532bd6fdc3010a153c01c38/68747470733a2f2f696d672e736869656c64732e696f2f6d6176656e2d63656e7472616c2f762f6f72672e6170616368652e7a6f6f6b65657065722f7a6f6f6b6565706572" alt="梅文中心" data-canonical-src="https://img.shields.io/maven-central/v/org.apache.zookeeper/zookeeper" style="max-width: 100%;"></a> <a href="https://github.com/apache/zookeeper/blob/master/LICENSE.txt"><img src="https://camo.githubusercontent.com/f5aa4624ec5ea8c4e3e9bed4e21b0c1ae3df77168f9931c4f8a8348f64724cc6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6170616368652f7a6f6f6b65657065723f636f6c6f723d323832363631" alt="执照" data-canonical-src="https://img.shields.io/github/license/apache/zookeeper?color=282661" style="max-width: 100%;"></a></h1>
<p align="left" dir="auto">
  <a href="https://zookeeper.apache.org/" rel="nofollow">
    <img src="https://camo.githubusercontent.com/8303e90dc4518b90f9ac230fe1e981fb929956efb2f6dc0f0855d48f8f21676a/68747470733a2f2f7a6f6f6b65657065722e6170616368652e6f72672f696d616765732f7a6f6f6b65657065725f736d616c6c2e676966" alt="https://zookeeper.apache.org/" data-animated-image="" data-canonical-src="https://zookeeper.apache.org/images/zookeeper_small.gif" style="max-width: 100%;"><br>
  </a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Apache ZooKeeper 的最新信息，请访问我们的网站：</font></font></p>
<p dir="auto"><a href="https://zookeeper.apache.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://zookeeper.apache.org</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及我们的维基百科，网址为：</font></font></p>
<p dir="auto"><a href="https://cwiki.apache.org/confluence/display/ZOOKEEPER" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://cwiki.apache.org/confluence/display/ZOOKEEPER</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-packagingrelease-artifacts" class="anchor" aria-hidden="true" tabindex="-1" href="#packagingrelease-artifacts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打包/发布工件</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://zookeeper.apache.org/releases.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以从https://zookeeper.apache.org/releases.html</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font><font style="vertical-align: inherit;">，也可以在使用maven构建项目后在zookeeper-assemble/target目录中找到。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>apache-zookeeper-[version].tar.gz

    Contains all the source files which can be built by running:
    mvn clean install

    To generate an aggregated apidocs for zookeeper-server and zookeeper-jute:
    mvn javadoc:aggregate
    (generated files will be at target/site/apidocs)

apache-zookeeper-[version]-bin.tar.gz

    Contains all the jar files required to run ZooKeeper
    Full documentation can also be found in the docs folder
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="apache-zookeeper-[version].tar.gz

    Contains all the source files which can be built by running:
    mvn clean install

    To generate an aggregated apidocs for zookeeper-server and zookeeper-jute:
    mvn javadoc:aggregate
    (generated files will be at target/site/apidocs)

apache-zookeeper-[version]-bin.tar.gz

    Contains all the jar files required to run ZooKeeper
    Full documentation can also be found in the docs folder" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从版本 3.5.5 开始，在 Apache ZooKeeper PMC 对版本进行投票并批准后，父级、zookeeper 和 Zookeeper-jute 工件将部署到中央存储库：</font></font></p>
<p dir="auto"><a href="https://repo1.maven.org/maven2/org/apache/zookeeper/zookeeper" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://repo1.maven.org/maven2/org/apache/zookeeper/zookeeper</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-java-8" class="anchor" aria-hidden="true" tabindex="-1" href="#java-8"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">爪哇8</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果要使用 Java 1.8 进行编译，则应使用 u211 或更高版本的最新版本。</font></font></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们始终欢迎新的贡献者加入该项目！</font><font style="vertical-align: inherit;">有关如何将补丁作为拉取请求提交以及我们的贡献工作流程的其他方面的详细信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://cwiki.apache.org/confluence/display/ZOOKEEPER/HowToContribute" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何贡献。</font></font></a><font style="vertical-align: inherit;"></font></p>
</article></div>

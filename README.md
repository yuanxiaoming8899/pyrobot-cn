<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://www.pyrobot.org/" rel="nofollow"><img src="/facebookresearch/pyrobot/raw/main/docs/website/website/static/img/pyrobot.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://www.pyrobot.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyRobot</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个轻量级的高级接口，为机器人操作和导航提供独立于硬件的 API。</font></font><a href="http://locobot.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库还包含LoCoBot</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（一种低成本移动机械手硬件平台）</font><font style="vertical-align: inherit;">的低级堆栈。</font></font></p>
<ul dir="auto">
<li><a href="#what-can-you-do-with-pyrobot"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你可以用 PyRobot 做什么？</font></font></a></li>
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><a href="#getting-started"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></a></li>
<li><a href="#the-team"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队</font></font></a></li>
<li><a href="#citation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></a></li>
<li><a href="#license"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
<li><a href="#Future-features"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未来的特点</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-what-can-you-do-with-pyrobot" class="anchor" aria-hidden="true" tabindex="-1" href="#what-can-you-do-with-pyrobot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你可以用 PyRobot 做什么？</font></font></h2>
<p align="center" dir="auto">
    <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/8b07206d6acdb4e75cabdb315e66d8e2eeb5678ac8089a9d0059946ea67e1c6e/68747470733a2f2f7468756d62732e6766796361742e636f6d2f4669636b6c655370656564794368696d6e657973776966742d73697a655f726573747269637465642e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/8b07206d6acdb4e75cabdb315e66d8e2eeb5678ac8089a9d0059946ea67e1c6e/68747470733a2f2f7468756d62732e6766796361742e636f6d2f4669636b6c655370656564794368696d6e657973776966742d73697a655f726573747269637465642e676966" height="180" data-canonical-src="https://thumbs.gfycat.com/FickleSpeedyChimneyswift-size_restricted.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/8b07206d6acdb4e75cabdb315e66d8e2eeb5678ac8089a9d0059946ea67e1c6e/68747470733a2f2f7468756d62732e6766796361742e636f6d2f4669636b6c655370656564794368696d6e657973776966742d73697a655f726573747269637465642e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/8b07206d6acdb4e75cabdb315e66d8e2eeb5678ac8089a9d0059946ea67e1c6e/68747470733a2f2f7468756d62732e6766796361742e636f6d2f4669636b6c655370656564794368696d6e657973776966742d73697a655f726573747269637465642e676966" height="180">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/8b07206d6acdb4e75cabdb315e66d8e2eeb5678ac8089a9d0059946ea67e1c6e/68747470733a2f2f7468756d62732e6766796361742e636f6d2f4669636b6c655370656564794368696d6e657973776966742d73697a655f726573747269637465642e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
    <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/ac4b66668441d313217505b9c973e5f937a87915a7324b4a5b835b9705481087/68747470733a2f2f7468756d62732e6766796361742e636f6d2f46696e69736865645765697264436f636b65727370616e69656c2d73697a655f726573747269637465642e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/ac4b66668441d313217505b9c973e5f937a87915a7324b4a5b835b9705481087/68747470733a2f2f7468756d62732e6766796361742e636f6d2f46696e69736865645765697264436f636b65727370616e69656c2d73697a655f726573747269637465642e676966" height="180" data-canonical-src="https://thumbs.gfycat.com/FinishedWeirdCockerspaniel-size_restricted.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/ac4b66668441d313217505b9c973e5f937a87915a7324b4a5b835b9705481087/68747470733a2f2f7468756d62732e6766796361742e636f6d2f46696e69736865645765697264436f636b65727370616e69656c2d73697a655f726573747269637465642e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/ac4b66668441d313217505b9c973e5f937a87915a7324b4a5b835b9705481087/68747470733a2f2f7468756d62732e6766796361742e636f6d2f46696e69736865645765697264436f636b65727370616e69656c2d73697a655f726573747269637465642e676966" height="180">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/ac4b66668441d313217505b9c973e5f937a87915a7324b4a5b835b9705481087/68747470733a2f2f7468756d62732e6766796361742e636f6d2f46696e69736865645765697264436f636b65727370616e69656c2d73697a655f726573747269637465642e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
    <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/a847c7f5ca0e7071f828d59250f86d753ca6d01bd7ec8310510f445fbfee80c1/68747470733a2f2f7468756d62732e6766796361742e636f6d2f576569676874794c656164696e67477275622d73697a655f726573747269637465642e676966" data-target="animated-image.originalLink" hidden=""><img src="https://camo.githubusercontent.com/a847c7f5ca0e7071f828d59250f86d753ca6d01bd7ec8310510f445fbfee80c1/68747470733a2f2f7468756d62732e6766796361742e636f6d2f576569676874794c656164696e67477275622d73697a655f726573747269637465642e676966" height="180" data-canonical-src="https://thumbs.gfycat.com/WeightyLeadingGrub-size_restricted.gif" style="max-width: 100%;" data-target="animated-image.originalImage" hidden=""></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/a847c7f5ca0e7071f828d59250f86d753ca6d01bd7ec8310510f445fbfee80c1/68747470733a2f2f7468756d62732e6766796361742e636f6d2f576569676874794c656164696e67477275622d73697a655f726573747269637465642e676966" target="_blank">
          <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/a847c7f5ca0e7071f828d59250f86d753ca6d01bd7ec8310510f445fbfee80c1/68747470733a2f2f7468756d62732e6766796361742e636f6d2f576569676874794c656164696e67477275622d73697a655f726573747269637465642e676966" height="180">
          </span>
        </a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1"></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="在新窗口中打开" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/a847c7f5ca0e7071f828d59250f86d753ca6d01bd7ec8310510f445fbfee80c1/68747470733a2f2f7468756d62732e6766796361742e636f6d2f576569676874794c656164696e67477275622d73697a655f726573747269637465642e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-installing-both-pyrobot-and-locobot-dependencies" class="anchor" aria-hidden="true" tabindex="-1" href="#installing-both-pyrobot-and-locobot-dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 PyRobot 和 LoCoBot 依赖项</font></font></h3>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 16.04</font></font></strong></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载安装脚本</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>sudo apt update
sudo apt-get install curl
curl <span class="pl-s"><span class="pl-pds">'</span>https://raw.githubusercontent.com/facebookresearch/pyrobot/main/robots/LoCoBot/install/locobot_install_all.sh<span class="pl-pds">'</span></span> <span class="pl-k">&gt;</span> locobot_install_all.sh</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sudo apt update
sudo apt-get install curl
curl 'https://raw.githubusercontent.com/facebookresearch/pyrobot/main/robots/LoCoBot/install/locobot_install_all.sh' > locobot_install_all.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行脚本来安装所有内容（ROS、realsense 驱动程序等）。</font></font></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用真正的LoCoBot机器人，请运行以下命令：
</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在运行以下命令之前将nuc机器连接到realsense相机</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span>-t Decides the type of installation. Available Options: full or sim_only</span>
<span class="pl-c"><span class="pl-c">#</span>-p Decides the python version for pyRobot. Available Options: 2 or 3</span>
<span class="pl-c"><span class="pl-c">#</span>-l Decides the type of LoCoBot hardware platform. Available Options: cmu or interbotix</span>
chmod +x locobot_install_all.sh
./locobot_install_all.sh -t full -p 2 -l interbotix</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#-t Decides the type of installation. Available Options: full or sim_only
#-p Decides the python version for pyRobot. Available Options: 2 or 3
#-l Decides the type of LoCoBot hardware platform. Available Options: cmu or interbotix
chmod +x locobot_install_all.sh
./locobot_install_all.sh -t full -p 2 -l interbotix" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您只想在 Gazebo 中使用模拟 LoCoBot，请运行以下命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span>-t Decides the type of installation. Available Options: full or sim_only</span>
<span class="pl-c"><span class="pl-c">#</span>-p Decides the python version for pyRobot. Available Options: 2 or 3</span>
<span class="pl-c"><span class="pl-c">#</span>-l Decides the type of LoCoBot hardware platform. Available Options: cmu or interbotix</span>
chmod +x locobot_install_all.sh
./locobot_install_all.sh -t sim_only -p 2 -l interbotix</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="#-t Decides the type of installation. Available Options: full or sim_only
#-p Decides the python version for pyRobot. Available Options: 2 or 3
#-l Decides the type of LoCoBot hardware platform. Available Options: cmu or interbotix
chmod +x locobot_install_all.sh
./locobot_install_all.sh -t sim_only -p 2 -l interbotix" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：要安装Python 3兼容的PyRobot，请</font><font style="vertical-align: inherit;">在上述命令中修改</font></font><code>-p 2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为。</font></font><code>-p 3</code><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-installing-just-pyrobot" class="anchor" aria-hidden="true" tabindex="-1" href="#installing-just-pyrobot"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅安装 PyRobot</font></font></h3>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ubuntu 16.04</font></font></strong></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font><a href="http://wiki.ros.org/kinetic/Installation/Ubuntu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS 动力学</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 PyRobot</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">cd</span> <span class="pl-k">~</span>
mkdir -p low_cost_ws/src
<span class="pl-c1">cd</span> <span class="pl-k">~</span>/low_cost_ws/src
git clone --recurse-submodules https://github.com/facebookresearch/pyrobot.git
<span class="pl-c1">cd</span> pyrobot/
chmod +x install_pyrobot.sh
./install_pyrobot.sh -p 2  <span class="pl-c"><span class="pl-c">#</span>For python3, modify the argumet to -p 3 </span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="cd ~
mkdir -p low_cost_ws/src
cd ~/low_cost_ws/src
git clone --recurse-submodules https://github.com/facebookresearch/pyrobot.git
cd pyrobot/
chmod +x install_pyrobot.sh
./install_pyrobot.sh -p 2  #For python3, modify the argumet to -p 3 " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：随着realsense不断更新，如果您不小心从</font></font><code>Software Updater</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ubuntu中更新了realsense相关的软件包，可能会出现兼容性问题。</font><font style="vertical-align: inherit;">因此，我们建议您不要更新任何与realsense相关的库。</font><font style="vertical-align: inherit;">当ubuntu提示软件更新时，请仔细检查更新列表。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入门</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://pyrobot.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pyrobot.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://locobot.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">locobot.org</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-the-team" class="anchor" aria-hidden="true" tabindex="-1" href="#the-team"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队</font></font></h2>
<p dir="auto"><a href="http://adithyamurali.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Adithya Murali</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://taochenshh.github.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陈涛</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="http://www.cs.cmu.edu/~dgandhi/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dhiraj Gandhi</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、Kalyan Vasudev、</font></font><a href="http://www.cs.cmu.edu/~lerrelp/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lerrel Pinto</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="http://saurabhg.web.illinois.edu" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Saurabh Gupta</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="http://www.cs.cmu.edu/~abhinavg/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Abhinav Gupta</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">我们还要感谢所有以任何方式帮助 PyRobot 的人。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-future-features" class="anchor" aria-hidden="true" tabindex="-1" href="#future-features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未来的特点</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们正在规划几个功能，即：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><a href="https://aihabitat.org" rel="nofollow"><font style="vertical-align: inherit;">与AI Habitat</font></a><font style="vertical-align: inherit;">等其他模拟器交互</font></font><a href="https://aihabitat.org" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重力补偿</font></font></li>
<li><font style="vertical-align: inherit;"><a href="https://www.universal-robots.com" rel="nofollow"><font style="vertical-align: inherit;">UR5</font></a><font style="vertical-align: inherit;">的 PyRobot 界面</font></font><a href="https://www.universal-robots.com" rel="nofollow"><font style="vertical-align: inherit;"></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-citation" class="anchor" aria-hidden="true" tabindex="-1" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h2>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@article{pyrobot2019,
  title={PyRobot: An Open-source Robotics Framework for Research and Benchmarking},
  author={Adithyavairavan Murali and Tao Chen and Kalyan Vasudev Alwala and Dhiraj Gandhi and Lerrel Pinto and Saurabh Gupta and Abhinav Gupta},
  journal={arXiv preprint arXiv:1906.08236},
  year={2019}
}
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{pyrobot2019,
  title={PyRobot: An Open-source Robotics Framework for Research and Benchmarking},
  author={Adithyavairavan Murali and Tao Chen and Kalyan Vasudev Alwala and Dhiraj Gandhi and Lerrel Pinto and Saurabh Gupta and Abhinav Gupta},
  journal={arXiv preprint arXiv:1906.08236},
  year={2019}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PyRobot 受 MIT 许可，如 LICENSE 文件中所示。</font></font></p>
</article></div>

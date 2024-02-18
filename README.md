<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://gatus.io" rel="nofollow"><img src="https://github.com/TwiN/gatus/raw/master/.github/assets/logo-with-dark-text.png" alt="加图斯" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/TwiN/gatus/workflows/test/badge.svg?branch=master"><img src="https://github.com/TwiN/gatus/workflows/test/badge.svg?branch=master" alt="测试" style="max-width: 100%;"></a>
<a href="https://goreportcard.com/report/github.com/TwiN/gatus" rel="nofollow"><img src="https://camo.githubusercontent.com/3f7298c2fc88d63d8923ff68a484279e05968b024c06cf54064bc2f65c91e5b7/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f6769746875622e636f6d2f5477694e2f67617475733f" alt="去报告卡" data-canonical-src="https://goreportcard.com/badge/github.com/TwiN/gatus?" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/TwiN/gatus" rel="nofollow"><img src="https://camo.githubusercontent.com/f3626efc64b8683c289cb9d7e4f1685d24aa8d9ec34e2dac6d44c262470d54bd/68747470733a2f2f636f6465636f762e696f2f67682f5477694e2f67617475732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="代码科夫" data-canonical-src="https://codecov.io/gh/TwiN/gatus/branch/master/graph/badge.svg" style="max-width: 100%;"></a>
<a href="https://github.com/TwiN/gatus"><img src="https://camo.githubusercontent.com/bada9f11581d4f6cc6d44a5f4ab9a484c360d8e5e273eda29023d0819c566362/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f676f2d6d6f642f676f2d76657273696f6e2f5477694e2f67617475732e737667" alt="去版本" data-canonical-src="https://img.shields.io/github/go-mod/go-version/TwiN/gatus.svg" style="max-width: 100%;"></a>
<a href="https://cloud.docker.com/repository/docker/twinproduction/gatus" rel="nofollow"><img src="https://camo.githubusercontent.com/d0799ebea43b7ad6fa763f83c5eb47921311be73445e71c8b4b3c4fbee504b65/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f7477696e70726f64756374696f6e2f67617475732e737667" alt="Docker 拉取" data-canonical-src="https://img.shields.io/docker/pulls/twinproduction/gatus.svg" style="max-width: 100%;"></a>
<a href="https://github.com/TwiN"><img src="https://camo.githubusercontent.com/15159fed1bf2129e45b91180736fd2aed922de63b051259494012e5c2f2551c6/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f666f6c6c6f776572732f5477694e3f6c6162656c3d466f6c6c6f77267374796c653d736f6369616c" alt="关注双子" data-canonical-src="https://img.shields.io/github/followers/TwiN?label=Follow&amp;style=social" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus 是一个面向开发人员的运行状况仪表板，使您能够使用 HTTP、ICMP、TCP 甚至 DNS 查询来监控您的服务，并通过使用状态代码等值的条件列表来评估所述查询的结果，响应时间、证书过期、正文等等。最重要的是，这些运行状况检查中的每一项都可以与通过 Slack、Teams、PagerDuty、Discord、Twilio 等发出的警报配对。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我亲自将它部署在我的 Kubernetes 集群中，并让它监控我的核心应用程序的状态：</font></font><a href="https://status.twin.sh/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https ://status.twin.sh/</font></font></a></p>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正在寻找托管解决方案？查看</font></font><a href="https://gatus.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus.io</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></em></p>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></b></summary>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --name gatus twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --name gatus twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">You can also use GitHub Container Registry if you prefer:</p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --name gatus ghcr.io/twin/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --name gatus ghcr.io/twin/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">For more details, see <a href="#usage">Usage</a></p>
</details>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">❤ 喜欢这个项目吗？请考虑</font></font><a href="https://github.com/sponsors/TwiN"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赞助我</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/dashboard-dark.png"><img src="/TwiN/gatus/raw/master/.github/assets/dashboard-dark.png" alt="佳图斯仪表板" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有任何反馈或问题吗？</font></font><a href="https://github.com/TwiN/gatus/discussions/new"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">创建讨论</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" tabindex="-1" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h2>
<ul dir="auto">
<li><a href="#table-of-contents"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></a></li>
<li><a href="#why-gatus"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么是加图斯？</font></font></a></li>
<li><a href="#features"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></a></li>
<li><a href="#usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></a></li>
<li><a href="#configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font></a>
<ul dir="auto">
<li><a href="#conditions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状况</font></font></a>
<ul dir="auto">
<li><a href="#placeholders"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符</font></font></a></li>
<li><a href="#functions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></a></li>
</ul>
</li>
<li><a href="#storage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贮存</font></font></a></li>
<li><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a></li>
<li><a href="#alerting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报</font></font></a>
<ul dir="auto">
<li><a href="#configuring-discord-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置不和谐警报</font></font></a></li>
<li><a href="#configuring-email-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置电子邮件警报</font></font></a></li>
<li><a href="#configuring-github-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitHub 警报</font></font></a></li>
<li><a href="#configuring-gitlab-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitLab 警报</font></font></a></li>
<li><a href="#configuring-google-chat-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Google 聊天提醒</font></font></a></li>
<li><a href="#configuring-gotify-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Gotify 警报</font></font></a></li>
<li><a href="#configuring-matrix-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置矩阵警报</font></font></a></li>
<li><a href="#configuring-mattermost-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Mattermost 警报</font></font></a></li>
<li><a href="#configuring-messagebird-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Messagebird 警报</font></font></a></li>
<li><a href="#configuring-ntfy-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Ntfy 警报</font></font></a></li>
<li><a href="#configuring-opsgenie-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Opsgenie 警报</font></font></a></li>
<li><a href="#configuring-pagerduty-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 PagerDuty 警报</font></font></a></li>
<li><a href="#configuring-pushover-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Pushover 警报</font></font></a></li>
<li><a href="#configuring-slack-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Slack 警报</font></font></a></li>
<li><a href="#configuring-teams-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Teams 警报</font></font></a></li>
<li><a href="#configuring-telegram-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Telegram 警报</font></font></a></li>
<li><a href="#configuring-twilio-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Twilio 警报</font></font></a></li>
<li><a href="#configuring-aws-ses-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 AWS SES 警报</font></font></a></li>
<li><a href="#configuring-custom-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置自定义警报</font></font></a></li>
<li><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></li>
</ul>
</li>
<li><a href="#maintenance"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护</font></font></a></li>
<li><a href="#security"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全</font></font></a>
<ul dir="auto">
<li><a href="#basic-authentication"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本认证</font></font></a></li>
<li><a href="#oidc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式数据中心</font></font></a></li>
</ul>
</li>
<li><a href="#tls-encryption"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传输层安全性 (TLS) 加密</font></font></a></li>
<li><a href="#metrics"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标</font></font></a></li>
<li><a href="#connectivity"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接性</font></font></a></li>
<li><a href="#remote-instances-experimental"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程实例（实验）</font></font></a></li>
</ul>
</li>
<li><a href="#deployment"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署</font></font></a>
<ul dir="auto">
<li><a href="#docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></a></li>
<li><a href="#helm-chart"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">舵图</font></font></a></li>
<li><a href="#terraform"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地形</font></font></a></li>
</ul>
</li>
<li><a href="#running-the-tests"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行测试</font></font></a></li>
<li><a href="#using-in-production"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在生产中使用</font></font></a></li>
<li><a href="#faq"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></a>
<ul dir="auto">
<li><a href="#sending-a-graphql-request"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送 GraphQL 请求</font></font></a></li>
<li><a href="#recommended-interval"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐间隔</font></font></a></li>
<li><a href="#default-timeouts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认超时</font></font></a></li>
<li><a href="#monitoring-a-tcp-endpoint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 TCP 端点</font></font></a></li>
<li><a href="#monitoring-a-udp-endpoint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 UDP 端点</font></font></a></li>
<li><a href="#monitoring-a-sctp-endpoint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 SCTP 端点</font></font></a></li>
<li><a href="#monitoring-a-websocket-endpoint"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 WebSocket 端点</font></font></a></li>
<li><a href="#monitoring-an-endpoint-using-icmp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 ICMP 监控端点</font></font></a></li>
<li><a href="#monitoring-an-endpoint-using-dns-queries"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 DNS 查询监控端点</font></font></a></li>
<li><a href="#monitoring-an-endpoint-using-ssh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SSH 监控端点</font></font></a></li>
<li><a href="#monitoring-an-endpoint-using-starttls"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 STARTTLS 监控端点</font></font></a></li>
<li><a href="#monitoring-an-endpoint-using-tls"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 TLS 监控端点</font></font></a></li>
<li><a href="#monitoring-domain-expiration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控域名过期</font></font></a></li>
<li><a href="#disable-monitoring-lock"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用监控锁定</font></font></a></li>
<li><a href="#reloading-configuration-on-the-fly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即时重新加载配置</font></font></a></li>
<li><a href="#endpoint-groups"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点组</font></font></a></li>
<li><a href="#exposing-gatus-on-a-custom-path"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在自定义路径上公开 Gatus</font></font></a></li>
<li><a href="#exposing-gatus-on-a-custom-port"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在自定义端口上公开 Gatus</font></font></a></li>
<li><a href="#configuring-a-startup-delay"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置启动延迟</font></font></a></li>
<li><a href="#keeping-your-configuration-small"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持较小的配置</font></font></a></li>
<li><a href="#proxy-client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理客户端配置</font></font></a></li>
<li><a href="#badges"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">徽章</font></font></a>
<ul dir="auto">
<li><a href="#uptime"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正常运行时间</font></font></a></li>
<li><a href="#health"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">健康</font></font></a></li>
<li><a href="#health-shieldsio"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">健康 (Shields.io)</font></font></a></li>
<li><a href="#response-time"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应时间</font></font></a>
<ul dir="auto">
<li><a href="#how-to-change-the-color-thresholds-of-the-response-time-badge"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何更改响应时间徽章的颜色阈值</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#api"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序编程接口</font></font></a></li>
<li><a href="#installing-as-binary"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为二进制安装</font></font></a></li>
<li><a href="#high-level-design-overview"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高层设计概述</font></font></a></li>
</ul>
</li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-why-gatus" class="anchor" aria-hidden="true" tabindex="-1" href="#why-gatus"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么是加图斯？</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在讨论具体细节之前，我想先解决一个最常见的问题：</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当我只能使用 Prometheus 的 Alertmanager、Cloudwatch 甚至 Splunk 时，为什么还要使用 Gatus？</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果没有客户端主动调用端点，这些都不能告诉您存在问题。换句话说，这是因为监控指标主要依赖于现有流量，这实际上意味着除非您的客户已经遇到问题，否则您不会收到通知。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另一方面，Gatus 允许您为每个功能配置运行状况检查，这反过来又允许它监视这些功能，并可能在任何客户端受到影响之前向您发出警报。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能想要研究 Gatus 的一个迹象是，只需询问自己，如果您的负载均衡器现在停机，您是否会收到警报。您现有的警报会被触发吗？如果没有流量到达您的应用程序，您的指标不会报告错误增加。这会让你陷入这样一种情况：你的客户会通知你服务质量下降，而不是你在他们知道之前向他们保证你正在努力解决问题。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-features" class="anchor" aria-hidden="true" tabindex="-1" href="#features"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">特征</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus的主要特点是：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高度灵活的健康检查条件</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：虽然检查响应状态对于某些用例来说可能就足够了，但 Gatus 更进一步，允许您添加有关响应时间、响应正文甚至 IP 地址的条件。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">能够使用 Gatus 进行用户验收测试</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：由于上述几点，您可以利用此应用程序来创建自动化的用户验收测试。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非常容易配置</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：不仅配置设计得尽可能可读，而且添加新服务或新端点以进行监控也非常容易。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：虽然拥有漂亮的可视化仪表板对于跟踪应用程序的状态很有用，但您可能不想整天盯着它。因此，开箱即用地支持通过 Slack、Mattermost、Messagebird、PagerDuty、Twilio、Google 聊天和 Teams 发出的通知，并且能够根据您可能有的任何需求配置自定义警报提供程序，无论是不同的提供程序还是自定义应用程序管理自动回滚。</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标</font></font></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">资源消耗低</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：与大多数 Go 应用程序一样，该应用程序所需的资源占用非常小，可以忽略不计。</font></font></li>
<li><strong><a href="#badges"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">徽章</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/288b204a02deb21b3bf01adc37b5513315877973944162c87c901b89c6990316/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f37642f62616467652e737667"><img src="https://camo.githubusercontent.com/288b204a02deb21b3bf01adc37b5513315877973944162c87c901b89c6990316/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f37642f62616467652e737667" alt="正常运行时间7天" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/7d/badge.svg" style="max-width: 100%;"></a> <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/005f146a3c088615ab3b34243a2ca42263bbedae69a9b40477f11eb55fae9b1f/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f3234682f62616467652e737667"><img src="https://camo.githubusercontent.com/005f146a3c088615ab3b34243a2ca42263bbedae69a9b40477f11eb55fae9b1f/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f3234682f62616467652e737667" alt="响应时间24小时" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/response-times/24h/badge.svg" style="max-width: 100%;"></a></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">深色模式</font></font></strong></li>
</ul>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/dashboard-conditions.png"><img src="/TwiN/gatus/raw/master/.github/assets/dashboard-conditions.png" alt="Gatus 仪表板状况" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h2>
<details>
  <summary><b><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></b></summary>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --name gatus twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --name gatus twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">You can also use GitHub Container Registry if you prefer:</p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --name gatus ghcr.io/twin/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --name gatus ghcr.io/twin/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto">If you want to create your own configuration, see <a href="#docker">Docker</a> for information on how to mount a configuration file.</p>
</details>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个简单的例子：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website                 </span><span class="pl-c"><span class="pl-c">#</span> Name of your endpoint, can be anything</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>                  <span class="pl-c"><span class="pl-c">#</span> Duration to wait between every status check (default: 60s)</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>         <span class="pl-c"><span class="pl-c">#</span> Status must be 200</span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>     <span class="pl-c"><span class="pl-c">#</span> The json path "$.status" must be equal to UP</span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>   <span class="pl-c"><span class="pl-c">#</span> Response time must be under 300ms</span>

  - <span class="pl-ent">name</span>: <span class="pl-s">make-sure-header-is-rendered</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">60s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>                          <span class="pl-c"><span class="pl-c">#</span> Status must be 200</span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY] == pat(*&lt;h1&gt;Example Domain&lt;/h1&gt;*)<span class="pl-pds">"</span></span> <span class="pl-c"><span class="pl-c">#</span> Body must contain the specified header</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: website                 # Name of your endpoint, can be anything
    url: &quot;https://twin.sh/health&quot;
    interval: 5m                  # Duration to wait between every status check (default: 60s)
    conditions:
      - &quot;[STATUS] == 200&quot;         # Status must be 200
      - &quot;[BODY].status == UP&quot;     # The json path &quot;$.status&quot; must be equal to UP
      - &quot;[RESPONSE_TIME] < 300&quot;   # Response time must be under 300ms

  - name: make-sure-header-is-rendered
    url: &quot;https://example.org/&quot;
    interval: 60s
    conditions:
      - &quot;[STATUS] == 200&quot;                          # Status must be 200
      - &quot;[BODY] == pat(*<h1>Example Domain</h1>*)&quot; # Body must contain the specified header" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这个例子看起来类似于：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/example.png"><img src="/TwiN/gatus/raw/master/.github/assets/example.png" alt="简单的例子" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，配置文件应位于</font></font><code>config/config.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过设置环境变量来指定自定义路径</font></font><code>GATUS_CONFIG_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>GATUS_CONFIG_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指向一个目录，则</font><font style="vertical-align: inherit;">该目录及其子目录中的所有文件都会像这样合并</font></font><code>*.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font><code>*.yml</code><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><code>alerting.slack</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有地图/对象都深度合并（即您可以在一个文件和</font></font><code>alerting.pagerduty</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">另一个文件中</font><font style="vertical-align: inherit;">定义）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有切片/数组都被附加（即您可以</font></font><code>endpoints</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在多个文件中定义，每个端点将被添加到最终的端点列表中）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有原始值的参数（例如</font></font><code>debug</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>metrics</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>alerting.slack.webhook-url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等）只能定义一次，以强制避免任何歧义
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">澄清一下，这也意味着您不能</font></font><code>alerting.slack.webhook-url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在两个文件中定义不同的值。所有文件在处理之前都会合并为一个。这是设计使然。</font></font></li>
</ul>
</li>
</ul>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💡 还可以在配置文件中使用环境变量（例如</font></font><code>$DOMAIN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>${DOMAIN}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关示例，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="/TwiN/gatus/blob/master/.examples/docker-compose-postgres-storage/config/config.yaml"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">examples/docker-compose-postgres-storage/config/config.yaml 。</font></font></a><font style="vertical-align: inherit;"></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想在本地测试它，请参阅</font></font><a href="#docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font></h2>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>debug</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否启用调试日志。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>metrics</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否在 /metrics 处公开指标。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>storage</code></td>
<td align="left"><a href="#storage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储配置</font></font></a></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>endpoints</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要监视的端点列表。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].enabled</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否监控端点。</font></font></td>
<td align="left"><code>true</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].name</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点的名称。可以是任何东西。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队名字。用于在仪表板上将多个端点分组在一起。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#endpoint-groups"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点组</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将请求发送到的 URL。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].method</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求方法。</font></font></td>
<td align="left"><code>GET</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].conditions</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于确定端点运行状况的条件。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#conditions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">条件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].interval</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每次状态检查之间等待的时间。</font></font></td>
<td align="left"><code>60s</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].graphql</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否将正文包装在查询参数 ( </font></font><code>{"query":"$body"}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">) 中。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].body</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求正文。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].headers</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求标头。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].dns</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DNS 类型端点的配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#monitoring-an-endpoint-using-dns-queries"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 DNS 查询监控端点</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].dns.query-type</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查询类型（例如 MX）</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].dns.query-name</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查询名称（例如 example.com）</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ssh</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSH 类型端点的配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#monitoring-an-endpoint-using-ssh"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SSH 监控端点</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ssh.username</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSH 用户名（例如示例）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ssh.password</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSH密码（例如密码）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].type</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报类型。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font><font style="vertical-align: inherit;">所有有效类型的</font></font><a href="#alerting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报。</font></font></a><font style="vertical-align: inherit;"></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].enabled</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否开启提醒。</font></font></td>
<td align="left"><code>true</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].failure-threshold</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">触发警报之前所需的连续失败次数。</font></font></td>
<td align="left"><code>3</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].success-threshold</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将正在进行的事件标记为已解决之前连续成功的次数。</font></font></td>
<td align="left"><code>2</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].send-on-resolved</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦触发的警报标记为已解决，是否发送通知。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].alerts[].description</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报的描述。将包含在发送的警报中。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].client</code></td>
<td align="left"><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ui</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点级别的 UI 配置。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ui.hide-hostname</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否在结果中隐藏主机名。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ui.hide-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否保证URL不显示在结果中。如果 URL 包含令牌，则很有用。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ui.dont-resolve-failed-conditions</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否解决 UI 的失败条件。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>endpoints[].ui.badge.reponse-time</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应时间阈值列表。每次达到阈值时，徽章都会有不同的颜色。</font></font></td>
<td align="left"><code>[50, 200, 300, 500, 750]</code></td>
</tr>
<tr>
<td align="left"><code>alerting</code></td>
<td align="left"><a href="#alerting"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>security</code></td>
<td align="left"><a href="#security"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>disable-monitoring-lock</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否</font></font><a href="#disable-monitoring-lock"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用监控锁</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>skip-invalid-config-update</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否忽略无效的配置更新。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#reloading-configuration-on-the-fly"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态重新加载配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>web</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页配置。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>web.address</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">收听地址。</font></font></td>
<td align="left"><code>0.0.0.0</code></td>
</tr>
<tr>
<td align="left"><code>web.port</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要侦听的端口。</font></font></td>
<td align="left"><code>8080</code></td>
</tr>
<tr>
<td align="left"><code>web.read-buffer-size</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从连接读取请求的缓冲区大小。还限制最大标头大小。</font></font></td>
<td align="left"><code>8192</code></td>
</tr>
<tr>
<td align="left"><code>web.tls.certificate-file</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PEM 格式的 TLS 可选公共证书文件。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">``</font></font></td>
</tr>
<tr>
<td align="left"><code>web.tls.private-key-file</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PEM 格式的 TLS 可选私钥文件。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">``</font></font></td>
</tr>
<tr>
<td align="left"><code>ui</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户界面配置。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>ui.title</code></td>
<td align="left"><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档的标题</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>Health Dashboard ǀ Gatus</code></td>
</tr>
<tr>
<td align="left"><code>ui.description</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">页面的元描述。</font></font></td>
<td align="left"><code>Gatus is an advanced...</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
</tr>
<tr>
<td align="left"><code>ui.header</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仪表板顶部的标题。</font></font></td>
<td align="left"><code>Health Status</code></td>
</tr>
<tr>
<td align="left"><code>ui.logo</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要显示的徽标的 URL。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>ui.link</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击徽标时打开链接。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>ui.buttons</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示在标题下方的按钮列表。</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>ui.buttons[].name</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示在按钮上的文本。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>ui.buttons[].link</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单击按钮时打开链接。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>maintenance</code></td>
<td align="left"><a href="#maintenance"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
</tbody>
</table>
<h3 tabindex="-1" dir="auto"><a id="user-content-conditions" class="anchor" aria-hidden="true" tabindex="-1" href="#conditions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状况</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是您可以使用的一些条件示例：</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">健康）状况</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传递值</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">失败的价值观</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>[STATUS] == 200</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态必须等于 200</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">200</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">201、404、...</font></font></td>
</tr>
<tr>
<td align="left"><code>[STATUS] &lt; 300</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态必须低于 300</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">200、201、299</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">301、302、……</font></font></td>
</tr>
<tr>
<td align="left"><code>[STATUS] &lt;= 299</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态必须小于或等于 299</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">200、201、299</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">301、302、……</font></font></td>
</tr>
<tr>
<td align="left"><code>[STATUS] &gt; 400</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态必须大于 400</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">401、402、403、404</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">400、200、...</font></font></td>
</tr>
<tr>
<td align="left"><code>[STATUS] == any(200, 429)</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">状态必须为 200 或 429</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">200, 429</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">201、400、...</font></font></td>
</tr>
<tr>
<td align="left"><code>[CONNECTED] == true</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与主机的连接必须已成功</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">错误的</font></font></td>
</tr>
<tr>
<td align="left"><code>[RESPONSE_TIME] &lt; 500</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应时间必须低于 500ms</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100毫秒、200毫秒、300毫秒</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">500毫秒、501毫秒</font></font></td>
</tr>
<tr>
<td align="left"><code>[IP] == 127.0.0.1</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标IP必须是127.0.0.1</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">127.0.0.1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.0.0.0</font></font></td>
</tr>
<tr>
<td align="left"><code>[BODY] == 1</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主体必须等于 1</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><code>{}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, ...</font></font></td>
</tr>
<tr>
<td align="left"><code>[BODY].user.name == john</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 值</font></font><code>$.user.name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等于</font></font><code>john</code></td>
<td align="left"><code>{"user":{"name":"john"}}</code></td>
<td></td>
</tr>
<tr>
<td align="left"><code>[BODY].data[0].id == 1</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 值</font></font><code>$.data[0].id</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等于 1</font></font></td>
<td align="left"><code>{"data":[{"id":1}]}</code></td>
<td></td>
</tr>
<tr>
<td align="left"><code>[BODY].age == [BODY].id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 值</font></font><code>$.age</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等于 JSONPath</font></font><code>$.id</code></td>
<td align="left"><code>{"age":1,"id":1}</code></td>
<td></td>
</tr>
<tr>
<td align="left"><code>len([BODY].data) &lt; 5</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 处的数组</font></font><code>$.data</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">少于 5 个元素</font></font></td>
<td align="left"><code>{"data":[{"id":1}]}</code></td>
<td></td>
</tr>
<tr>
<td align="left"><code>len([BODY].name) == 8</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 处的字符串</font></font><code>$.name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">长度为 8</font></font></td>
<td align="left"><code>{"name":"john.doe"}</code></td>
<td><code>{"name":"bob"}</code></td>
</tr>
<tr>
<td align="left"><code>has([BODY].errors) == false</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath</font></font><code>$.errors</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不存在</font></font></td>
<td align="left"><code>{"name":"john.doe"}</code></td>
<td><code>{"errors":[]}</code></td>
</tr>
<tr>
<td align="left"><code>has([BODY].users) == true</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath</font></font><code>$.users</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存在</font></font></td>
<td align="left"><code>{"users":[]}</code></td>
<td><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>[BODY].name == pat(john*)</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 中的字符串与</font></font><code>$.name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式匹配</font></font><code>john*</code></td>
<td align="left"><code>{"name":"john.doe"}</code></td>
<td><code>{"name":"bob"}</code></td>
</tr>
<tr>
<td align="left"><code>[BODY].id == any(1, 2)</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONPath 的值</font></font><code>$.id</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等于</font></font><code>1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>2</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1, 2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3, 4, 5</font></font></td>
</tr>
<tr>
<td align="left"><code>[CERTIFICATE_EXPIRATION] &gt; 48h</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">距离证书到期还有 48 小时以上</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">49小时、50小时、123小时</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1小时、24小时、...</font></font></td>
</tr>
<tr>
<td align="left"><code>[DOMAIN_EXPIRATION] &gt; 720h</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">域名必须在 720 小时内过期</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4000小时</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1小时、24小时、...</font></font></td>
</tr>
</tbody>
</table>
<h4 tabindex="-1" dir="auto"><a id="user-content-placeholders" class="anchor" aria-hidden="true" tabindex="-1" href="#placeholders"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析值示例</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>[STATUS]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为请求的 HTTP 状态</font></font></td>
<td align="left"><code>404</code></td>
</tr>
<tr>
<td align="left"><code>[RESPONSE_TIME]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为请求所花费的响应时间（以毫秒为单位）</font></font></td>
<td align="left"><code>10</code></td>
</tr>
<tr>
<td align="left"><code>[IP]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为目标主机的IP</font></font></td>
<td align="left"><code>192.168.0.232</code></td>
</tr>
<tr>
<td align="left"><code>[BODY]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为响应正文。支持 JSONPath。</font></font></td>
<td align="left"><code>{"name":"john.doe"}</code></td>
</tr>
<tr>
<td align="left"><code>[CONNECTED]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析是否可以建立连接</font></font></td>
<td align="left"><code>true</code></td>
</tr>
<tr>
<td align="left"><code>[CERTIFICATE_EXPIRATION]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为证书过期之前的持续时间（有效单位为“s”、“m”、“h”。）</font></font></td>
<td align="left"><code>24h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>48h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, 0（如果没有带有证书的协议）</font></font></td>
</tr>
<tr>
<td align="left"><code>[DOMAIN_EXPIRATION]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为域过期之前的持续时间（有效单位为“s”、“m”、“h”。）</font></font></td>
<td align="left"><code>24h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>48h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>1234h56m78s</code></td>
</tr>
<tr>
<td align="left"><code>[DNS_RCODE]</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为响应的 DNS 状态</font></font></td>
<td align="left"><code>NOERROR</code></td>
</tr>
</tbody>
</table>
<h4 tabindex="-1" dir="auto"><a id="user-content-functions" class="anchor" aria-hidden="true" tabindex="-1" href="#functions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>len</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果给定路径通向数组，则返回其长度。否则，给定路径处的 JSON 将被缩小并转换为字符串，并返回结果字符数。仅适用于</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符。</font></font></td>
<td align="left"><code>len([BODY].username) &gt; 8</code></td>
</tr>
<tr>
<td align="left"><code>has</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">返回</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>false</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于给定路径是否有效。仅适用于</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符。</font></font></td>
<td align="left"><code>has([BODY].errors) == false</code></td>
</tr>
<tr>
<td align="left"><code>pat</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指定作为参数传递的字符串应被评估为模式。仅适用于</font></font><code>==</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>!=</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>[IP] == pat(192.168.*)</code></td>
</tr>
<tr>
<td align="left"><code>any</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指定作为参数传递的任何一个值都是有效值。仅适用于</font></font><code>==</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>!=</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>[BODY].ip == any(127.0.0.1, ::1)</code></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>pat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💡仅在需要时</font><font style="vertical-align: inherit;">使用。</font></font><code>[STATUS] == pat(2*)</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比 贵很多</font></font><code>[STATUS] &lt; 300</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-storage" class="anchor" aria-hidden="true" tabindex="-1" href="#storage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贮存</font></font></h3>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>storage</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>storage.path</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保存数据的路径。仅支持类型</font></font><code>sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>storage.type</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">存储类型。有效类型：</font></font><code>memory</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></td>
<td align="left"><code>"memory"</code></td>
</tr>
<tr>
<td align="left"><code>storage.caching</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否使用直写式缓存。缩短大型仪表板的加载时间。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅当</font></font><code>storage.type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或时才支持</font></font><code>postgres</code></td>
<td align="left"><code>false</code></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个端点运行状况检查的结果以及正常运行时间和过去事件的数据必须保留，以便可以显示在仪表板上。这些参数允许您配置相关存储。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>storage.type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>memory</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（默认）：</font></font></li>
</ul>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Note that this is the default value, and you can omit the storage configuration altogether to achieve the same result.</span>
<span class="pl-c"><span class="pl-c">#</span> Because the data is stored in memory, the data will not survive a restart.</span>
<span class="pl-ent">storage</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">memory</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Note that this is the default value, and you can omit the storage configuration altogether to achieve the same result.
# Because the data is stored in memory, the data will not survive a restart.
storage:
  type: memory" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>storage.type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>sqlite</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则</font></font><code>storage.path</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不能为空：</font></font></li>
</ul>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">storage</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">sqlite</span>
  <span class="pl-ent">path</span>: <span class="pl-s">data.db</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="storage:
  type: sqlite
  path: data.db" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关示例，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="/TwiN/gatus/blob/master/.examples/docker-compose-sqlite-storage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Examples/docker-compose-sqlite-storage 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>storage.type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>postgres</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>storage.path</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">则必须是连接 URL：</font></font></li>
</ul>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">storage</span>:
  <span class="pl-ent">type</span>: <span class="pl-s">postgres</span>
  <span class="pl-ent">path</span>: <span class="pl-s"><span class="pl-pds">"</span>postgres://user:password@127.0.0.1:5432/gatus?sslmode=disable<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="storage:
  type: postgres
  path: &quot;postgres://user:password@127.0.0.1:5432/gatus?sslmode=disable&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关示例，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="/TwiN/gatus/blob/master/.examples/docker-compose-postgres-storage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Examples/docker-compose-postgres-storage 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-client-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#client-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了支持广泛的环境，每个受监视的端点都具有用于发送请求的客户端的唯一配置。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>client.insecure</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否跳过验证服务器的证书链和主机名。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>client.ignore-redirect</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否忽略重定向（true）或遵循重定向（false，默认值）。</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>client.timeout</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">超时前的持续时间。</font></font></td>
<td align="left"><code>10s</code></td>
</tr>
<tr>
<td align="left"><code>client.dns-resolver</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用格式覆盖 DNS 解析器</font></font><code>{proto}://{host}:{port}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.oauth2</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OAuth2 客户端配置。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>client.oauth2.token-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">令牌端点 URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.oauth2.client-id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用于的客户端 ID</font></font><code>Client credentials flow</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.oauth2.client-secret</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用于的客户端密钥</font></font><code>Client credentials flow</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.oauth2.scopes[]</code></td>
<td align="left"><font style="vertical-align: inherit;"></font><code>scopes</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应该使用其中</font><font style="vertical-align: inherit;">的列表</font></font><code>Client credentials flow</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>[""]</code></td>
</tr>
<tr>
<td align="left"><code>client.proxy-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于客户端的代理的 URL</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.identity-aware-proxy</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Identity-Aware-Proxy 客户端配置。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>client.identity-aware-proxy.audience</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">身份感知代理受众。 （IAP oauth2 凭证的客户端 ID）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>client.network</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于 ICMP 端点客户端的网络（</font></font><code>ip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>ip4</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>ip6</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font></td>
<td align="left"><code>"ip"</code></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 根据端点的类型，其中一些参数会被忽略。例如，ICMP 请求 (ping) 中不涉及证书，因此，对该类型的端点设置</font></font><code>client.insecure</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不会执行任何操作。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这个默认配置如下：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">client</span>:
  <span class="pl-ent">insecure</span>: <span class="pl-c1">false</span>
  <span class="pl-ent">ignore-redirect</span>: <span class="pl-c1">false</span>
  <span class="pl-ent">timeout</span>: <span class="pl-c1">10s</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="client:
  insecure: false
  ignore-redirect: false
  timeout: 10s" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>endpoints[]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，此配置仅在、</font></font><code>alerting.mattermost</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font><font style="vertical-align: inherit;">下可用</font></font><code>alerting.custom</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是客户端配置的示例</font></font><code>endpoints[]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">insecure</span>: <span class="pl-c1">false</span>
      <span class="pl-ent">ignore-redirect</span>: <span class="pl-c1">false</span>
      <span class="pl-ent">timeout</span>: <span class="pl-c1">10s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    client:
      insecure: false
      ignore-redirect: false
      timeout: 10s
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此示例显示如何指定自定义 DNS 解析器：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">with-custom-dns-resolver</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://your.health.api/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">dns-resolver</span>: <span class="pl-s"><span class="pl-pds">"</span>tcp://8.8.8.8:53<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: with-custom-dns-resolver
    url: &quot;https://your.health.api/health&quot;
    client:
      dns-resolver: &quot;tcp://8.8.8.8:53&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此示例展示了如何使用</font></font><code>client.oauth2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置来查询后端 API </font></font><code>Bearer token</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">with-custom-oauth2</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://your.health.api/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">oauth2</span>:
        <span class="pl-ent">token-url</span>: <span class="pl-s">https://your-token-server/token</span>
        <span class="pl-ent">client-id</span>: <span class="pl-s">00000000-0000-0000-0000-000000000000</span>
        <span class="pl-ent">client-secret</span>: <span class="pl-s">your-client-secret</span>
        <span class="pl-ent">scopes</span>: <span class="pl-s">['https://your.health.api/.default']</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: with-custom-oauth2
    url: &quot;https://your.health.api/health&quot;
    client:
      oauth2:
        token-url: https://your-token-server/token
        client-id: 00000000-0000-0000-0000-000000000000
        client-secret: your-client-secret
        scopes: ['https://your.health.api/.default']
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此示例展示了如何使用 Google Identity-Aware-Proxy</font></font><code>client.identity-aware-proxy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置来查询后端 API </font></font><code>Bearer token</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">with-custom-iap</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://my.iap.protected.app/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">identity-aware-proxy</span>:
        <span class="pl-ent">audience</span>: <span class="pl-s"><span class="pl-pds">"</span>XXXXXXXX-XXXXXXXXXXXX.apps.googleusercontent.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: with-custom-iap
    url: &quot;https://my.iap.protected.app/health&quot;
    client:
      identity-aware-proxy:
        audience: &quot;XXXXXXXX-XXXXXXXXXXXX.apps.googleusercontent.com&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 请注意，Gatus 将使用其环境中的</font></font><a href="https://cloud.google.com/docs/authentication/application-default-credentials" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gcloud 默认凭据</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来生成令牌。</font></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-alerting" class="anchor" aria-hidden="true" tabindex="-1" href="#alerting"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus 支持多个警报提供程序，例如 Slack 和 PagerDuty，并通过可配置的描述和阈值支持每个端点的不同警报。</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 如果警报提供程序未正确配置，则使用提供程序类型配置的所有警报都将被忽略。</font></font></p>
</blockquote>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.custom</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置针对故障或警报的自定义操作。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-custom-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置自定义警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>discord</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-discord-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Discord 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>email</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-email-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置电子邮件警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.github</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>github</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-github-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitHub 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>gitlab</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-gitlab-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitLab 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>googlechat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-google-chat-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Google Chat 提醒</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>gotify</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-gotify-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Gotify 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.matrix</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>matrix</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-matrix-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置矩阵警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>mattermost</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-mattermost-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Mattermost 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.messagebird</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>messagebird</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-messagebird-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Messagebird 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>ntfy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-ntfy-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Ntfy 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>opsgenie</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-opsgenie-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Opsgenie 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>pagerduty</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-pagerduty-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 PagerDuty 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>pushover</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-pushover-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Pushover 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.slack</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>slack</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-slack-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Slack 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.teams</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>teams</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-teams-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Teams 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>telegram</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-telegram-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Telegram 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的设置</font></font><code>twilio</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#configuring-twilio-alerts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Twilio 警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
</tbody>
</table>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-discord-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-discord-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置不和谐警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.discord</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>discord</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord Webhook URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.title</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通知标题</font></font></td>
<td align="left"><code>":helmet_with_white_cross: Gatus"</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.discord.overrides[].webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Discord Webhook URL</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">discord</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://discord.com/api/webhooks/**********/**********<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">discord</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  discord:
    webhook-url: &quot;https://discord.com/api/webhooks/**********/**********&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: discord
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-email-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-email-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置电子邮件警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.email</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>email</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.from</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于发送警报的电子邮件</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.username</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于发送警报的 SMTP 服务器的用户名。如果为空，则使用</font></font><code>alerting.email.from</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.password</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于发送警报的 SMTP 服务器的密码。如果为空，则不执行任何身份验证。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.host</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">邮件服务器的主机（例如</font></font><code>smtp.gmail.com</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.port</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">邮件服务器正在侦听的端口（例如</font></font><code>587</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>0</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.to</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将警报发送至的电子邮件地址</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.email.client.insecure</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否跳过TLS验证</font></font></td>
<td align="left"><code>false</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.email.overrides[].to</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将警报发送至的电子邮件地址</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">email</span>:
    <span class="pl-ent">from</span>: <span class="pl-s"><span class="pl-pds">"</span>from@example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">username</span>: <span class="pl-s"><span class="pl-pds">"</span>from@example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">password</span>: <span class="pl-s"><span class="pl-pds">"</span>hunter2<span class="pl-pds">"</span></span>
    <span class="pl-ent">host</span>: <span class="pl-s"><span class="pl-pds">"</span>mail.example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">port</span>: <span class="pl-c1">587</span>
    <span class="pl-ent">to</span>: <span class="pl-s"><span class="pl-pds">"</span>recipient1@example.com,recipient2@example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">insecure</span>: <span class="pl-c1">false</span>
    <span class="pl-c"><span class="pl-c">#</span> You can also add group-specific to keys, which will</span>
    <span class="pl-c"><span class="pl-c">#</span> override the to key above for the specified groups</span>
    <span class="pl-ent">overrides</span>:
      - <span class="pl-ent">group</span>: <span class="pl-s"><span class="pl-pds">"</span>core<span class="pl-pds">"</span></span>
        <span class="pl-ent">to</span>: <span class="pl-s"><span class="pl-pds">"</span>recipient3@example.com,recipient4@example.com<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">email</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>

  - <span class="pl-ent">name</span>: <span class="pl-s">back-end</span>
    <span class="pl-ent">group</span>: <span class="pl-s">core</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 48h<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">email</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  email:
    from: &quot;from@example.com&quot;
    username: &quot;from@example.com&quot;
    password: &quot;hunter2&quot;
    host: &quot;mail.example.com&quot;
    port: 587
    to: &quot;recipient1@example.com,recipient2@example.com&quot;
    client:
      insecure: false
    # You can also add group-specific to keys, which will
    # override the to key above for the specified groups
    overrides:
      - group: &quot;core&quot;
        to: &quot;recipient3@example.com,recipient4@example.com&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: email
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true

  - name: back-end
    group: core
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 48h&quot;
    alerts:
      - type: email
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠ 有些邮件服务器速度慢得令人痛苦。</font></font></p>
</blockquote>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-github-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-github-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitHub 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.github</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>github</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.github.repository-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 存储库 URL（例如</font></font><code>https://github.com/TwiN/example</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.github.token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于身份验证的个人访问令牌。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须至少有关于问题的 RW 和关于元数据的 RO。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.github.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub 警报提供程序</font></font><code>alert(gatus):</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个警报创建一个以端点显示名称为前缀和后缀的问题。如果在端点警报上</font></font><code>send-on-resolved</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则警报解决后问题将自动关闭。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">github</span>:
    <span class="pl-ent">repository-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://github.com/TwiN/test<span class="pl-pds">"</span></span>
    <span class="pl-ent">token</span>: <span class="pl-s"><span class="pl-pds">"</span>github_pat_12345...<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 75<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">github</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">2</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>Everything's burning AAAAAHHHHHHHHHHHHHHH<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  github:
    repository-url: &quot;https://github.com/TwiN/test&quot;
    token: &quot;github_pat_12345...&quot;

endpoints:
  - name: example
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 75&quot;
    alerts:
      - type: github
        failure-threshold: 2
        success-threshold: 3
        send-on-resolved: true
        description: &quot;Everything's burning AAAAAHHHHHHHHHHHHHHH&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/github-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/github-alerts.png" alt="GitHub 警报" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-gitlab-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-gitlab-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 GitLab 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.gitlab</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>gitlab</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitLab 警报 Webhook URL（例如</font></font><code>https://gitlab.com/hlidotbe/example/alerts/notify/gatus/xxxxxxxxxxxxxxxx.json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.authorization-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于身份验证的个人访问令牌。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须至少有关于问题的 RW 和关于元数据的 RO。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.severity</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">覆盖默认严重性（严重），可以是以下之一</font></font><code>critical, high, medium, low, info, unknown</code></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.monitoring-tool</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">覆盖监控工具名称（gatus）</font></font></td>
<td align="left"><code>"gatus"</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.environment-name</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置gitlab环境的名称。需要在仪表板上显示警报。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.service</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">覆盖端点显示名称</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gitlab.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitLab 警报提供程序创建一个警报，该警报的前缀</font></font><code>alert(gatus):</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和后缀为每个警报的端点显示名称。如果在端点警报上</font></font><code>send-on-resolved</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则警报解决后警报将自动关闭。请参阅
</font></font><a href="https://docs.gitlab.com/ee/operations/incident_management/integrations.html#configuration" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://docs.gitlab.com/ee/operations/incident_management/integrations.html#configuration</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置端点。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">gitlab</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://gitlab.com/hlidotbe/example/alerts/notify/gatus/xxxxxxxxxxxxxxxx.json<span class="pl-pds">"</span></span>
    <span class="pl-ent">authorization-key</span>: <span class="pl-s"><span class="pl-pds">"</span>12345<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 75<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">gitlab</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">2</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>Everything's burning AAAAAHHHHHHHHHHHHHHH<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  gitlab:
    webhook-url: &quot;https://gitlab.com/hlidotbe/example/alerts/notify/gatus/xxxxxxxxxxxxxxxx.json&quot;
    authorization-key: &quot;12345&quot;

endpoints:
  - name: example
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 75&quot;
    alerts:
      - type: gitlab
        failure-threshold: 2
        success-threshold: 3
        send-on-resolved: true
        description: &quot;Everything's burning AAAAAHHHHHHHHHHHHHHH&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/gitlab-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/gitlab-alerts.png" alt="亚搏体育appGitLab警报" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-google-chat-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-google-chat-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Google 聊天提醒</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.googlechat</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>googlechat</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google 聊天 Webhook 网址</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.client</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.googlechat.overrides[].webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google 聊天 Webhook 网址</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">googlechat</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://chat.googleapis.com/v1/spaces/*******/messages?key=**********&amp;token=********<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">googlechat</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  googlechat:
    webhook-url: &quot;https://chat.googleapis.com/v1/spaces/*******/messages?key=**********&amp;token=********&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: googlechat
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-gotify-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-gotify-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Gotify 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.gotify</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>gotify</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify.server-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取服务器 URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify.token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于身份验证的令牌。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify.priority</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据 Gotify 标准的警报优先级。</font></font></td>
<td align="left"><code>5</code></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.gotify.title</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通知标题</font></font></td>
<td align="left"><code>"Gatus: &lt;endpoint&gt;"</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">gotify</span>:
    <span class="pl-ent">server-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://gotify.example<span class="pl-pds">"</span></span>
    <span class="pl-ent">token</span>: <span class="pl-s"><span class="pl-pds">"</span>**************<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">gotify</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  gotify:
    server-url: &quot;https://gotify.example&quot;
    token: &quot;**************&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: gotify
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是通知的示例：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/gotify-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/gotify-alerts.png" alt="通知通知" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-matrix-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-matrix-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置矩阵警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.matrix</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>matrix</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.matrix.server-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">家庭服务器网址</font></font></td>
<td align="left"><code>https://matrix-client.matrix.org</code></td>
</tr>
<tr>
<td align="left"><code>alerting.matrix.access-token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人用户访问令牌（请参阅</font></font><a href="https://webapps.stackexchange.com/q/131056" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://webapps.stackexchange.com/q/131056</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.matrix.internal-room-id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要将警报发送到的房间的内部房间 ID（可以在房间设置 &gt; 高级中找到）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.matrix.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">matrix</span>:
    <span class="pl-ent">server-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://matrix-client.matrix.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">access-token</span>: <span class="pl-s"><span class="pl-pds">"</span>123456<span class="pl-pds">"</span></span>
    <span class="pl-ent">internal-room-id</span>: <span class="pl-s"><span class="pl-pds">"</span>!example:matrix.org<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">matrix</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  matrix:
    server-url: &quot;https://matrix-client.matrix.org&quot;
    access-token: &quot;123456&quot;
    internal-room-id: &quot;!example:matrix.org&quot;

endpoints:
  - name: website
    interval: 5m
    url: &quot;https://twin.sh/health&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: matrix
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-mattermost-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-mattermost-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Mattermost 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.mattermost</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>mattermost</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mattermost Webhook URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost.client</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermost.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.mattermist.overrides[].webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mattermost Webhook URL</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">mattermost</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>http://**********/hooks/**********<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">insecure</span>: <span class="pl-c1">true</span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">mattermost</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  mattermost:
    webhook-url: &quot;http://**********/hooks/**********&quot;
    client:
      insecure: true

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: mattermost
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是通知的示例：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/mattermost-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/mattermost-alerts.png" alt="最重要的通知" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-messagebird-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-messagebird-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Messagebird 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.messagebird</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>messagebird</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.messagebird.access-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Messagebird 访问密钥</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.messagebird.originator</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息的发送者</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.messagebird.recipients</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">消息的接收者</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.messagebird.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Messagebird发送短信警报的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">messagebird</span>:
    <span class="pl-ent">access-key</span>: <span class="pl-s"><span class="pl-pds">"</span>...<span class="pl-pds">"</span></span>
    <span class="pl-ent">originator</span>: <span class="pl-s"><span class="pl-pds">"</span>31619191918<span class="pl-pds">"</span></span>
    <span class="pl-ent">recipients</span>: <span class="pl-s"><span class="pl-pds">"</span>31619191919,31619191920<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">messagebird</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  messagebird:
    access-key: &quot;...&quot;
    originator: &quot;31619191918&quot;
    recipients: &quot;31619191919,31619191920&quot;

endpoints:
  - name: website
    interval: 5m
    url: &quot;https://twin.sh/health&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: messagebird
        failure-threshold: 3
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-ntfy-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-ntfy-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Ntfy 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.ntfy</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>ntfy</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy.topic</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将发送警报的主题</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy.url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标服务器的URL</font></font></td>
<td align="left"><code>https://ntfy.sh</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy.token</code></td>
<td align="left"><a href="https://docs.ntfy.sh/publish/#access-tokens" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">受限主题的</font><a href="https://docs.ntfy.sh/publish/#access-tokens" rel="nofollow"><font style="vertical-align: inherit;">访问令牌</font></a></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy.priority</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报的优先级</font></font></td>
<td align="left"><code>3</code></td>
</tr>
<tr>
<td align="left"><code>alerting.ntfy.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><a href="https://github.com/binwiederhier/ntfy"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ntfy</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个令人惊叹的项目，它允许您订阅桌面和移动通知，使其成为 Gatus 的一个很棒的补充。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">ntfy</span>:
    <span class="pl-ent">topic</span>: <span class="pl-s"><span class="pl-pds">"</span>gatus-test-topic<span class="pl-pds">"</span></span>
    <span class="pl-ent">priority</span>: <span class="pl-c1">2</span>
    <span class="pl-ent">token</span>: <span class="pl-s">faketoken</span>
    <span class="pl-ent">default-alert</span>:
      <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
      <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">ntfy</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  ntfy:
    topic: &quot;gatus-test-topic&quot;
    priority: 2
    token: faketoken
    default-alert:
      failure-threshold: 3
      send-on-resolved: true

endpoints:
  - name: website
    interval: 5m
    url: &quot;https://twin.sh/health&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: ntfy" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-opsgenie-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-opsgenie-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Opsgenie 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.opsgenie</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>opsgenie</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.api-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Opsgenie API 密钥</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.priority</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报的优先级。</font></font></td>
<td align="left"><code>P1</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.source</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报的源字段。</font></font></td>
<td align="left"><code>gatus</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.entity-prefix</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实体字段前缀。</font></font></td>
<td align="left"><code>gatus-</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.alias-prefix</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">别名字段前缀。</font></font></td>
<td align="left"><code>gatus-healthcheck-</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.tags</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报标签。</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.opsgenie.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Opsgenie 提供商将自动打开和关闭警报。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">opsgenie</span>:
    <span class="pl-ent">api-key</span>: <span class="pl-s"><span class="pl-pds">"</span>00000000-0000-0000-0000-000000000000<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  opsgenie:
    api-key: &quot;00000000-0000-0000-0000-000000000000&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-pagerduty-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-pagerduty-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 PagerDuty 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.pagerduty</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>pagerduty</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty.integration-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PagerDuty 事件 API v2 集成密钥</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty.overrides[].integration-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PagerDuty 事件 API v2 集成密钥</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pagerduty.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强烈建议将</font><font style="vertical-align: inherit;">类型的警报设置</font></font><code>endpoints[].alerts[].send-on-resolved</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font><font style="vertical-align: inherit;">，因为与其他警报不同，将所述参数设置为 所产生的操作</font><font style="vertical-align: inherit;">不会创建另一个事件，而是在 PagerDuty 上将该事件标记为已解决。</font></font><code>true</code><font style="vertical-align: inherit;"></font><code>pagerduty</code><font style="vertical-align: inherit;"></font><code>true</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">行为：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，</font></font><code>alerting.pagerduty.integration-key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用作集成密钥</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果正在评估的端点属于与</font></font><code>endpoints[].group</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">值匹配的组 ( ) </font></font><code>alerting.pagerduty.overrides[].group</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则提供程序将使用该覆盖的集成密钥而不是</font></font><code>alerting.pagerduty.integration-key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></li>
</ul>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">pagerduty</span>:
    <span class="pl-ent">integration-key</span>: <span class="pl-s"><span class="pl-pds">"</span>********************************<span class="pl-pds">"</span></span>
    <span class="pl-c"><span class="pl-c">#</span> You can also add group-specific integration keys, which will</span>
    <span class="pl-c"><span class="pl-c">#</span> override the integration key above for the specified groups</span>
    <span class="pl-ent">overrides</span>:
      - <span class="pl-ent">group</span>: <span class="pl-s"><span class="pl-pds">"</span>core<span class="pl-pds">"</span></span>
        <span class="pl-ent">integration-key</span>: <span class="pl-s"><span class="pl-pds">"</span>********************************<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">pagerduty</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">back-end</span>
    <span class="pl-ent">group</span>: <span class="pl-s">core</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 48h<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">pagerduty</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  pagerduty:
    integration-key: &quot;********************************&quot;
    # You can also add group-specific integration keys, which will
    # override the integration key above for the specified groups
    overrides:
      - group: &quot;core&quot;
        integration-key: &quot;********************************&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: pagerduty
        failure-threshold: 3
        success-threshold: 5
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;

  - name: back-end
    group: core
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 48h&quot;
    alerts:
      - type: pagerduty
        failure-threshold: 3
        success-threshold: 5
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-pushover-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-pushover-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Pushover 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.pushover</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>pushover</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.application-token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pushover 应用令牌</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.user-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户或组密钥</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.title</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过 Pushover 发送的所有消息的固定标题</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pushover 中您的应用程序名称</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.priority</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有消息的优先级，范围从 -2（非常低）到 2（紧急）</font></font></td>
<td align="left"><code>0</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.sound</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有消息的声音</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看</font><font style="vertical-align: inherit;">所有有效选项的</font></font><a href="https://pushover.net/api#sounds" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">声音。</font></font></a><font style="vertical-align: inherit;"></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.pushover.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">pushover</span>:
    <span class="pl-ent">application-token</span>: <span class="pl-s"><span class="pl-pds">"</span>******************************<span class="pl-pds">"</span></span>
    <span class="pl-ent">user-key</span>: <span class="pl-s"><span class="pl-pds">"</span>******************************<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">pushover</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  pushover:
    application-token: &quot;******************************&quot;
    user-key: &quot;******************************&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: pushover
        failure-threshold: 3
        success-threshold: 5
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-slack-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-slack-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Slack 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.slack</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>slack</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.slack.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack Webhook URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.slack.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.slack.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.slack.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.slack.overrides[].webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack Webhook URL</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">slack</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://hooks.slack.com/services/**********/**********/**********<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed 3 times in a row<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed 5 times in a row<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  slack:
    webhook-url: &quot;https://hooks.slack.com/services/**********/**********/**********&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: slack
        description: &quot;healthcheck failed 3 times in a row&quot;
        send-on-resolved: true
      - type: slack
        failure-threshold: 5
        description: &quot;healthcheck failed 5 times in a row&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是通知的示例：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/slack-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/slack-alerts.png" alt="松弛通知" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-teams-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-teams-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Teams 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.teams</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>teams</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.teams.webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队 Webhook URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.teams.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.teams.overrides</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可能优先于默认配置的覆盖列表</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>alerting.teams.overrides[].group</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此配置将覆盖其配置的端点组</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.teams.overrides[].webhook-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队 Webhook URL</font></font></td>
<td align="left"><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">teams</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://********.webhook.office.com/webhookb2/************<span class="pl-pds">"</span></span>
    <span class="pl-c"><span class="pl-c">#</span> You can also add group-specific to keys, which will</span>
    <span class="pl-c"><span class="pl-c">#</span> override the to key above for the specified groups</span>
    <span class="pl-ent">overrides</span>:
      - <span class="pl-ent">group</span>: <span class="pl-s"><span class="pl-pds">"</span>core<span class="pl-pds">"</span></span>
        <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://********.webhook.office.com/webhookb3/************<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">teams</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>

  - <span class="pl-ent">name</span>: <span class="pl-s">back-end</span>
    <span class="pl-ent">group</span>: <span class="pl-s">core</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 48h<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">teams</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  teams:
    webhook-url: &quot;https://********.webhook.office.com/webhookb2/************&quot;
    # You can also add group-specific to keys, which will
    # override the to key above for the specified groups
    overrides:
      - group: &quot;core&quot;
        webhook-url: &quot;https://********.webhook.office.com/webhookb3/************&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: teams
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true

  - name: back-end
    group: core
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 48h&quot;
    alerts:
      - type: teams
        description: &quot;healthcheck failed&quot;
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是通知的示例：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/teams-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/teams-alerts.png" alt="团队通知" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-telegram-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-telegram-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Telegram 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.telegram</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型警报的配置</font></font><code>telegram</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram.token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Telegram 机器人令牌</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram.id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电报用户 ID</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram.api-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电报 API 网址</font></font></td>
<td align="left"><code>https://api.telegram.org</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram.client</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.telegram.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">telegram</span>:
    <span class="pl-ent">token</span>: <span class="pl-s"><span class="pl-pds">"</span>123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11<span class="pl-pds">"</span></span>
    <span class="pl-ent">id</span>: <span class="pl-s"><span class="pl-pds">"</span>0123456789<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">telegram</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  telegram:
    token: &quot;123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11&quot;
    id: &quot;0123456789&quot;

endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
    alerts:
      - type: telegram
        send-on-resolved: true" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是通知的示例：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/telegram-alerts.png"><img src="/TwiN/gatus/raw/master/.github/assets/telegram-alerts.png" alt="电报通知" style="max-width: 100%;"></a></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-twilio-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-twilio-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 Twilio 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.twilio</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报类型的设置</font></font><code>twilio</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio.sid</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Twilio 帐户 SID</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio.token</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Twilio 身份验证令牌</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio.from</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送 Twilio 警报的号码</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio.to</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送 twilio 警报的号码</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.twilio.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">twilio</span>:
    <span class="pl-ent">sid</span>: <span class="pl-s"><span class="pl-pds">"</span>...<span class="pl-pds">"</span></span>
    <span class="pl-ent">token</span>: <span class="pl-s"><span class="pl-pds">"</span>...<span class="pl-pds">"</span></span>
    <span class="pl-ent">from</span>: <span class="pl-s"><span class="pl-pds">"</span>+1-234-567-8901<span class="pl-pds">"</span></span>
    <span class="pl-ent">to</span>: <span class="pl-s"><span class="pl-pds">"</span>+1-234-567-8901<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">twilio</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  twilio:
    sid: &quot;...&quot;
    token: &quot;...&quot;
    from: &quot;+1-234-567-8901&quot;
    to: &quot;+1-234-567-8901&quot;

endpoints:
  - name: website
    interval: 30s
    url: &quot;https://twin.sh/health&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: twilio
        failure-threshold: 5
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-aws-ses-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-aws-ses-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置 AWS SES 警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.aws-ses</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报类型的设置</font></font><code>aws-ses</code></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.access-key-id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 访问密钥 ID</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选修的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.secret-access-key</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 秘密访问密钥</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选修的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.region</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AWS 区域</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.from</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送电子邮件的电子邮件地址（应在 SES 中注册）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.to</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要通知的电子邮件地址的逗号分隔列表</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.aws-ses.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">aws-ses</span>:
    <span class="pl-ent">access-key-id</span>: <span class="pl-s"><span class="pl-pds">"</span>...<span class="pl-pds">"</span></span>
    <span class="pl-ent">secret-access-key</span>: <span class="pl-s"><span class="pl-pds">"</span>...<span class="pl-pds">"</span></span>
    <span class="pl-ent">region</span>: <span class="pl-s"><span class="pl-pds">"</span>us-east-1<span class="pl-pds">"</span></span>
    <span class="pl-ent">from</span>: <span class="pl-s"><span class="pl-pds">"</span>status@example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">to</span>: <span class="pl-s"><span class="pl-pds">"</span>user@example.com<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">aws-ses</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>healthcheck failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  aws-ses:
    access-key-id: &quot;...&quot;
    secret-access-key: &quot;...&quot;
    region: &quot;us-east-1&quot;
    from: &quot;status@example.com&quot;
    to: &quot;user@example.com&quot;

endpoints:
  - name: website
    interval: 30s
    url: &quot;https://twin.sh/health&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: aws-ses
        failure-threshold: 5
        send-on-resolved: true
        description: &quot;healthcheck failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>access-key-id</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>secret-access-key</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">未定义，Gatus 将回退到 IAM 身份验证。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您有能力使用</font></font><code>ses:SendEmail</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-configuring-custom-alerts" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-custom-alerts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置自定义警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.custom</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置针对故障或警报的自定义操作</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义警报请求&ZeroWidthSpace;&ZeroWidthSpace; URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.method</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求方式</font></font></td>
<td align="left"><code>GET</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.body</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义警报请求&ZeroWidthSpace;&ZeroWidthSpace;正文。</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.headers</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自定义警报请求&ZeroWidthSpace;&ZeroWidthSpace;标头</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.client</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>alerting.custom.default-alert</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认警报配置。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#setting-a-default-alert"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然它们被称为警报，但您可以使用此功能来调用任何内容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，您可以通过使用跟踪新部署的应用程序来自动回滚，并且通过利用 Gatus，您可以让 Gatus 在端点开始出现故障时调用该应用程序端点。然后，您的应用程序将检查开始失败的端点是否是最近部署的应用程序的一部分，如果是，则自动将其回滚。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此外，您可以在正文 ( </font></font><code>alerting.custom.body</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">) 和 url ( </font></font><code>alerting.custom.url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">) 中使用以下占位符：</font></font></p>
<ul dir="auto">
<li><code>[ALERT_DESCRIPTION]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（从 解决</font></font><code>endpoints[].alerts[].description</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><code>[ENDPOINT_NAME]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（从 解决</font></font><code>endpoints[].name</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><code>[ENDPOINT_GROUP]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（从 解决</font></font><code>endpoints[].group</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
<li><code>[ENDPOINT_URL]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（从 解决</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有使用设置</font></font><code>custom</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 的提供程序的</font><font style="vertical-align: inherit;">警报</font><font style="vertical-align: inherit;">，则可以使用
</font><font style="vertical-align: inherit;">占位符来区分通知。上述占位符将被</font><font style="vertical-align: inherit;">或</font><font style="vertical-align: inherit;">相应地替换，尽管它可以被修改（详细信息在本节末尾）。</font></font><code>send-on-resolved</code><font style="vertical-align: inherit;"></font><code>true</code><font style="vertical-align: inherit;"></font><code>[ALERT_TRIGGERED_OR_RESOLVED]</code><font style="vertical-align: inherit;"></font><code>TRIGGERED</code><font style="vertical-align: inherit;"></font><code>RESOLVED</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">出于所有意图和目的，我们将使用 Slack Webhook 配置自定义警报，但您可以调用任何您想要的内容。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">custom</span>:
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://hooks.slack.com/services/**********/**********/**********<span class="pl-pds">"</span></span>
    <span class="pl-ent">method</span>: <span class="pl-s"><span class="pl-pds">"</span>POST<span class="pl-pds">"</span></span>
    <span class="pl-ent">body</span>: <span class="pl-s">|</span>
<span class="pl-s">      {</span>
<span class="pl-s">        "text": "[ALERT_TRIGGERED_OR_RESOLVED]: [ENDPOINT_GROUP] - [ENDPOINT_NAME] - [ALERT_DESCRIPTION]"</span>
<span class="pl-s">      }</span>
<span class="pl-s"></span><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[RESPONSE_TIME] &lt; 300<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">custom</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">10</span>
        <span class="pl-ent">success-threshold</span>: <span class="pl-c1">3</span>
        <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
        <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>health check failed<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  custom:
    url: &quot;https://hooks.slack.com/services/**********/**********/**********&quot;
    method: &quot;POST&quot;
    body: |
      {
        &quot;text&quot;: &quot;[ALERT_TRIGGERED_OR_RESOLVED]: [ENDPOINT_GROUP] - [ENDPOINT_NAME] - [ALERT_DESCRIPTION]&quot;
      }
endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    interval: 30s
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;
      - &quot;[RESPONSE_TIME] < 300&quot;
    alerts:
      - type: custom
        failure-threshold: 10
        success-threshold: 3
        send-on-resolved: true
        description: &quot;health check failed&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，您可以自定义占位符的解析值，</font></font><code>[ALERT_TRIGGERED_OR_RESOLVED]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如下所示：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">custom</span>:
    <span class="pl-ent">placeholders</span>:
      <span class="pl-ent">ALERT_TRIGGERED_OR_RESOLVED</span>:
        <span class="pl-ent">TRIGGERED</span>: <span class="pl-s"><span class="pl-pds">"</span>partial_outage<span class="pl-pds">"</span></span>
        <span class="pl-ent">RESOLVED</span>: <span class="pl-s"><span class="pl-pds">"</span>operational<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  custom:
    placeholders:
      ALERT_TRIGGERED_OR_RESOLVED:
        TRIGGERED: &quot;partial_outage&quot;
        RESOLVED: &quot;operational&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">因此，</font></font><code>[ALERT_TRIGGERED_OR_RESOLVED]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本节第一个示例正文中的 将会被替换
</font></font><code>partial_outage</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为何时触发警报和</font></font><code>operational</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">何时解决警报。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-setting-a-default-alert" class="anchor" aria-hidden="true" tabindex="-1" href="#setting-a-default-alert"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置默认警报</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>alerting.*.default-alert.enabled</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否开启提醒</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.*.default-alert.failure-threshold</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">触发警报之前所需的连续失败次数</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.*.default-alert.success-threshold</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将正在进行的事件标记为已解决之前连续成功的次数</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.*.default-alert.send-on-resolved</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦触发的警报标记为已解决，是否发送通知</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
<tr>
<td align="left"><code>alerting.*.default-alert.description</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警报的描述。将包含在发送的警报中</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不适用</font></font></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠即使您设置了提供商的默认警报，</font><font style="vertical-align: inherit;">您仍然必须在端点配置中指定警报的类型。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然您可以直接在端点定义中指定警报配置，但这很乏味，并且可能会导致配置文件很长。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了避免此类问题，您可以使用</font></font><code>default-alert</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个提供程序配置中存在的参数：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">slack</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://hooks.slack.com/services/**********/**********/**********<span class="pl-pds">"</span></span>
    <span class="pl-ent">default-alert</span>:
      <span class="pl-ent">description</span>: <span class="pl-s"><span class="pl-pds">"</span>health check failed<span class="pl-pds">"</span></span>
      <span class="pl-ent">send-on-resolved</span>: <span class="pl-c1">true</span>
      <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>
      <span class="pl-ent">success-threshold</span>: <span class="pl-c1">5</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  slack:
    webhook-url: &quot;https://hooks.slack.com/services/**********/**********/**********&quot;
    default-alert:
      description: &quot;health check failed&quot;
      send-on-resolved: true
      failure-threshold: 5
      success-threshold: 5" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">因此，您的 Gatus 配置看起来更加整洁：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>

  - <span class="pl-ent">name</span>: <span class="pl-s">other-example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example
    url: &quot;https://example.org&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
    alerts:
      - type: slack

  - name: other-example
    url: &quot;https://example.com&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
    alerts:
      - type: slack" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它还允许您执行以下操作：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">10</span>
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
        <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">15</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example
    url: &quot;https://example.org&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
    alerts:
      - type: slack
        failure-threshold: 5
      - type: slack
        failure-threshold: 10
      - type: slack
        failure-threshold: 15" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当然，您也可以混合警报类型：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">alerting</span>:
  <span class="pl-ent">slack</span>:
    <span class="pl-ent">webhook-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://hooks.slack.com/services/**********/**********/**********<span class="pl-pds">"</span></span>
    <span class="pl-ent">default-alert</span>:
      <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">3</span>
  <span class="pl-ent">pagerduty</span>:
    <span class="pl-ent">integration-key</span>: <span class="pl-s"><span class="pl-pds">"</span>********************************<span class="pl-pds">"</span></span>
    <span class="pl-ent">default-alert</span>:
      <span class="pl-ent">failure-threshold</span>: <span class="pl-c1">5</span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">endpoint-1</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
      - <span class="pl-ent">type</span>: <span class="pl-s">pagerduty</span>

  - <span class="pl-ent">name</span>: <span class="pl-s">endpoint-2</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
    <span class="pl-ent">alerts</span>:
      - <span class="pl-ent">type</span>: <span class="pl-s">slack</span>
      - <span class="pl-ent">type</span>: <span class="pl-s">pagerduty</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="alerting:
  slack:
    webhook-url: &quot;https://hooks.slack.com/services/**********/**********/**********&quot;
    default-alert:
      failure-threshold: 3
  pagerduty:
    integration-key: &quot;********************************&quot;
    default-alert:
      failure-threshold: 5

endpoints:
  - name: endpoint-1
    url: &quot;https://example.org&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
    alerts:
      - type: slack
      - type: pagerduty

  - name: endpoint-2
    url: &quot;https://example.org&quot;
    conditions:
      - &quot;[STATUS] == 200&quot;
    alerts:
      - type: slack
      - type: pagerduty" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-maintenance" class="anchor" aria-hidden="true" tabindex="-1" href="#maintenance"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有维护窗口，您可能不希望被警报打扰。为此，您必须使用维护配置：</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>maintenance.enabled</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否启用维护期</font></font></td>
<td align="left"><code>true</code></td>
</tr>
<tr>
<td align="left"><code>maintenance.start</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护窗口开始的时间，</font></font><code>hh:mm</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">格式为（例如</font></font><code>23:00</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>maintenance.duration</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护窗口的持续时间（例如</font></font><code>1h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>30m</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>maintenance.every</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维护期适用的天数（例如</font></font><code>[Monday, Thursday]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果留空，则维护时段每天适用</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 维护配置使用UTC</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个例子：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">maintenance</span>:
  <span class="pl-ent">start</span>: <span class="pl-c1">23:00</span>
  <span class="pl-ent">duration</span>: <span class="pl-c1">1h</span>
  <span class="pl-ent">every</span>: <span class="pl-s">[Monday, Thursday]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="maintenance:
  start: 23:00
  duration: 1h
  every: [Monday, Thursday]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，您还可以在单&ZeroWidthSpace;&ZeroWidthSpace;独的行中指定每一天：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">maintenance</span>:
  <span class="pl-ent">start</span>: <span class="pl-c1">23:00</span>
  <span class="pl-ent">duration</span>: <span class="pl-c1">1h</span>
  <span class="pl-ent">every</span>:
    - <span class="pl-s">Monday</span>
    - <span class="pl-s">Thursday</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="maintenance:
  start: 23:00
  duration: 1h
  every:
    - Monday
    - Thursday" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-security" class="anchor" aria-hidden="true" tabindex="-1" href="#security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全</font></font></h3>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>security</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>security.basic</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP基本配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenID 连接配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
</tbody>
</table>
<h4 tabindex="-1" dir="auto"><a id="user-content-basic-authentication" class="anchor" aria-hidden="true" tabindex="-1" href="#basic-authentication"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本认证</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>security.basic</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP基本配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>security.basic.username</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基本身份验证的用户名。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>security.basic.password-bcrypt-base64</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">密码使用 Bcrypt 进行哈希处理，然后使用 base64 进行编码以进行基本身份验证。</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的示例将要求您使用用户名</font></font><code>john.doe</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和密码进行身份验证</font></font><code>hunter2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">security</span>:
  <span class="pl-ent">basic</span>:
    <span class="pl-ent">username</span>: <span class="pl-s"><span class="pl-pds">"</span>john.doe<span class="pl-pds">"</span></span>
    <span class="pl-ent">password-bcrypt-base64</span>: <span class="pl-s"><span class="pl-pds">"</span>JDJhJDEwJHRiMnRFakxWazZLdXBzRERQazB1TE8vckRLY05Yb1hSdnoxWU0yQ1FaYXZRSW1McmladDYu<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="security:
  basic:
    username: &quot;john.doe&quot;
    password-bcrypt-base64: &quot;JDJhJDEwJHRiMnRFakxWazZLdXBzRERQazB1TE8vckRLY05Yb1hSdnoxWU0yQ1FaYXZRSW1McmladDYu&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠ 确保仔细选择 bcrypt 哈希的成本。成本越高，计算哈希值所需的时间就越长，并且基本身份验证会根据每个请求的哈希值验证密码。截至 2023 年 1 月 6 日，我建议成本为 9。</font></font></p>
</blockquote>
<h4 tabindex="-1" dir="auto"><a id="user-content-oidc" class="anchor" aria-hidden="true" tabindex="-1" href="#oidc"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放式数据中心</font></font></h4>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>security.oidc</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenID 连接配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.issuer-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发行人网址</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.redirect-url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重定向网址。必须以以下结尾</font></font><code>/authorization-code/callback</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.client-id</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户编号</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.client-secret</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户秘密</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.scopes</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求的范围。您需要的唯一范围是</font></font><code>openid</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>security.oidc.allowed-subjects</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">允许的科目列表。如果为空，则允许所有科目。</font></font></td>
<td align="left"><code>[]</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">security</span>:
  <span class="pl-ent">oidc</span>:
    <span class="pl-ent">issuer-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.okta.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">redirect-url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://status.example.com/authorization-code/callback<span class="pl-pds">"</span></span>
    <span class="pl-ent">client-id</span>: <span class="pl-s"><span class="pl-pds">"</span>123456789<span class="pl-pds">"</span></span>
    <span class="pl-ent">client-secret</span>: <span class="pl-s"><span class="pl-pds">"</span>abcdefghijk<span class="pl-pds">"</span></span>
    <span class="pl-ent">scopes</span>: <span class="pl-s">["openid"]</span>
    <span class="pl-c"><span class="pl-c">#</span> You may optionally specify a list of allowed subjects. If this is not specified, all subjects will be allowed.</span>
    <span class="pl-c"><span class="pl-c">#</span>allowed-subjects: ["johndoe@example.com"]</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="security:
  oidc:
    issuer-url: &quot;https://example.okta.com&quot;
    redirect-url: &quot;https://status.example.com/authorization-code/callback&quot;
    client-id: &quot;123456789&quot;
    client-secret: &quot;abcdefghijk&quot;
    scopes: [&quot;openid&quot;]
    # You may optionally specify a list of allowed subjects. If this is not specified, all subjects will be allowed.
    #allowed-subjects: [&quot;johndoe@example.com&quot;]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使困惑？阅读</font></font><a href="https://twin.sh/articles/56/securing-gatus-with-oidc-using-auth0" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Auth0 通过 OIDC 保护 Gatus</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-tls-encryption" class="anchor" aria-hidden="true" tabindex="-1" href="#tls-encryption"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传输层安全性 (TLS) 加密</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus 支持使用 TLS 进行基本加密。为此，必须提供 PEM 格式的证书文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的示例显示了一个示例配置，该配置使 gatus 在端口 4443 上响应 HTTPS 请求：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">web</span>:
  <span class="pl-ent">port</span>: <span class="pl-c1">4443</span>
  <span class="pl-ent">tls</span>:
    <span class="pl-ent">certificate-file</span>: <span class="pl-s"><span class="pl-pds">"</span>certificate.crt<span class="pl-pds">"</span></span>
    <span class="pl-ent">private-key-file</span>: <span class="pl-s"><span class="pl-pds">"</span>private.key<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="web:
  port: 4443
  tls:
    certificate-file: &quot;certificate.crt&quot;
    private-key-file: &quot;private.key&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-metrics" class="anchor" aria-hidden="true" tabindex="-1" href="#metrics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要启用指标，您必须设置</font></font><code>metrics</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这样做将</font></font><code>/metrics</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
在应用程序配置为运行的同一端口上的端点</font><font style="vertical-align: inherit;">上公开 Prometheus 友好的指标( </font></font><code>web.port</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标名称</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">类型</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标签</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相关端点类型</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gatus_结果_总计</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">柜台</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个端点的结果数</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键、组、名称、类型、成功</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gatus_结果_代码_总计</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">柜台</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按代码显示的结果总数</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键、组、名称、类型、代码</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">域名系统、HTTP</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gatus_results_connected_total</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">柜台</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成功建立连接的结果总数</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键、组、名称、类型</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gatus_results_duration_秒</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测量</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求的持续时间（以秒为单位）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键、组、名称、类型</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gatus_results_certificate_expiration_秒</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测量</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">距离证书过期还有多少秒</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键、组、名称、类型</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP、STARTTLS</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多文档和示例，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="/TwiN/gatus/blob/master/.examples/docker-compose-grafana-prometheus"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Examples/docker-compose-grafana-prometheus 。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-connectivity" class="anchor" aria-hidden="true" tabindex="-1" href="#connectivity"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接性</font></font></h3>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>connectivity</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>connectivity.checker</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接检查器配置</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>connectivity.checker.target</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于验证连接的主机</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
<tr>
<td align="left"><code>connectivity.checker.interval</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">验证连接的时间间隔</font></font></td>
<td align="left"><code>1m</code></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然 Gatus 用于监控其他服务，但 Gatus 本身可能会失去与互联网的连接。为了防止当 Gatus 本身不健康时 Gatus 报告端点不健康，您可以将 Gatus 配置为定期检查互联网连接。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当连接检查器认为连接已关闭时，所有端点执行都会被跳过。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">connectivity</span>:
  <span class="pl-ent">checker</span>:
    <span class="pl-ent">target</span>: <span class="pl-s">1.1.1.1:53</span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">60s</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="connectivity:
  checker:
    target: 1.1.1.1:53
    interval: 60s" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-remote-instances-experimental" class="anchor" aria-hidden="true" tabindex="-1" href="#remote-instances-experimental"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程实例（实验）</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此功能允许您从远程 Gatus 实例检索端点状态。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有两个主要用例：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您有多个 Gatus 实例在不同的计算机上运行，&ZeroWidthSpace;&ZeroWidthSpace;并且您希望通过单个仪表板直观地公开状态</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您有一个或多个不可公开访问的 Gatus 实例（例如在防火墙后面），并且您希望检索</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个实验性功能。它可能随时被删除或以破坏性的方式更新。此外，此功能还存在已知问题。如果您想提供一些反馈，请在</font></font><a href="https://github.com/TwiN/gatus/issues/64" data-hovercard-type="issue" data-hovercard-url="/TwiN/gatus/issues/64/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#64</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中发表评论。使用风险自负。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><code>remote</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程配置</font></font></td>
<td align="left"><code>{}</code></td>
</tr>
<tr>
<td align="left"><code>remote.instances</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远程实例列表</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>[]</code></td>
</tr>
<tr>
<td align="left"><code>remote.instances.endpoint-prefix</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有端点名称的前缀字符串</font></font></td>
<td align="left"><code>""</code></td>
</tr>
<tr>
<td align="left"><code>remote.instances.url</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从中检索端点状态的 URL</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必需的</font></font><code>""</code></td>
</tr>
</tbody>
</table>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">remote</span>:
  <span class="pl-ent">instances</span>:
    - <span class="pl-ent">endpoint-prefix</span>: <span class="pl-s"><span class="pl-pds">"</span>status.example.org-<span class="pl-pds">"</span></span>
      <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://status.example.org/api/v1/endpoints/statuses<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="remote:
  instances:
    - endpoint-prefix: &quot;status.example.org-&quot;
      url: &quot;https://status.example.org/api/v1/endpoints/statuses&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-deployment" class="anchor" aria-hidden="true" tabindex="-1" href="#deployment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/TwiN/gatus/blob/master/.examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.examples</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹中可以找到许多示例</font><font style="vertical-align: inherit;">，但本节将重点介绍部署 Gatus 的最流行方法。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-docker" class="anchor" aria-hidden="true" tabindex="-1" href="#docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">码头工人</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用 Docker 在本地运行 Gatus：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --name gatus twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --name gatus twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">除了使用</font></font><a href="/TwiN/gatus/blob/master/.examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.examples</font></font></a><font style="vertical-align: inherit;"></font><code>config.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹中提供的示例之一之外，您还可以通过创建一个配置文件（我们将在本示例中调用它）并运行以下命令来</font><font style="vertical-align: inherit;">在本地进行尝试：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --mount type=bind,source="$(pwd)"/config.yaml,target=/config/config.yaml --name gatus twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --mount type=bind,source=&quot;$(pwd)&quot;/config.yaml,target=/config/config.yaml --name gatus twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用的是 Windows，请替换</font></font><code>"$(pwd)"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为当前目录的绝对路径，例如：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker run -p 8080:8080 --mount type=bind,source=C:/Users/Chris/Desktop/config.yaml,target=/config/config.yaml --name gatus twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8080:8080 --mount type=bind,source=C:/Users/Chris/Desktop/config.yaml,target=/config/config.yaml --name gatus twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在本地构建镜像：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">docker build . -t twinproduction/gatus</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker build . -t twinproduction/gatus" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-helm-chart" class="anchor" aria-hidden="true" tabindex="-1" href="#helm-chart"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">舵图</font></font></h3>
<p dir="auto"><a href="https://helm.sh" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">必须安装Helm</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">才能使用图表。请参阅 Helm 的</font></font><a href="https://helm.sh/docs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来开始使用。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正确设置 Helm 后，添加存储库，如下所示：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">helm repo add minicloudlabs https://minicloudlabs.github.io/helm-charts</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="helm repo add minicloudlabs https://minicloudlabs.github.io/helm-charts" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要了解更多详细信息，请查看</font></font><a href="https://github.com/minicloudlabs/helm-charts/tree/main/charts/gatus#configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图表的配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
和</font></font><a href="https://github.com/minicloudlabs/helm-charts/tree/main/charts/gatus#helmfileyaml-example"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">helmfile 示例</font></font></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-terraform" class="anchor" aria-hidden="true" tabindex="-1" href="#terraform"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地形</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以使用以下模块将 Gatus 部署在 Terraform 上：</font></font><a href="https://github.com/TwiN/terraform-kubernetes-gatus"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">terraform-kubernetes-gatus</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-running-the-tests" class="anchor" aria-hidden="true" tabindex="-1" href="#running-the-tests"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行测试</font></font></h2>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">go test -v ./...</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="go test -v ./..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-using-in-production" class="anchor" aria-hidden="true" tabindex="-1" href="#using-in-production"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在生产中使用</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="#deployment"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-faq" class="anchor" aria-hidden="true" tabindex="-1" href="#faq"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">常问问题</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-sending-a-graphql-request" class="anchor" aria-hidden="true" tabindex="-1" href="#sending-a-graphql-request"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发送 GraphQL 请求</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过设置</font></font><code>endpoints[].graphql</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 true，主体将自动由标准 GraphQL</font></font><code>query</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数包装。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，以下配置：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">filter-users-by-gender</span>
    <span class="pl-ent">url</span>: <span class="pl-s">http://localhost:8080/playground</span>
    <span class="pl-ent">method</span>: <span class="pl-s">POST</span>
    <span class="pl-ent">graphql</span>: <span class="pl-c1">true</span>
    <span class="pl-ent">body</span>: <span class="pl-s">|</span>
<span class="pl-s">      {</span>
<span class="pl-s">        users(gender: "female") {</span>
<span class="pl-s">          id</span>
<span class="pl-s">          name</span>
<span class="pl-s">          gender</span>
<span class="pl-s">          avatar</span>
<span class="pl-s">        }</span>
<span class="pl-s">      }</span>
<span class="pl-s"></span>    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].data.users[0].gender == female<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: filter-users-by-gender
    url: http://localhost:8080/playground
    method: POST
    graphql: true
    body: |
      {
        users(gender: &quot;female&quot;) {
          id
          name
          gender
          avatar
        }
      }
    conditions:
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].data.users[0].gender == female&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将向</font><font style="vertical-align: inherit;">以下主体发送</font></font><code>POST</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请求：</font></font><code>http://localhost:8080/playground</code><font style="vertical-align: inherit;"></font></p>
<div class="highlight highlight-source-json notranslate position-relative overflow-auto" dir="auto"><pre>{<span class="pl-ent">"query"</span>:<span class="pl-s"><span class="pl-pds">"</span>      {<span class="pl-cce">\n</span>        users(gender: <span class="pl-cce">\"</span>female<span class="pl-cce">\"</span>) {<span class="pl-cce">\n</span>          id<span class="pl-cce">\n</span>          name<span class="pl-cce">\n</span>          gender<span class="pl-cce">\n</span>          avatar<span class="pl-cce">\n</span>        }<span class="pl-cce">\n</span>      }<span class="pl-pds">"</span></span>}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="{&quot;query&quot;:&quot;      {\n        users(gender: \&quot;female\&quot;) {\n          id\n          name\n          gender\n          avatar\n        }\n      }&quot;}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-recommended-interval" class="anchor" aria-hidden="true" tabindex="-1" href="#recommended-interval"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐间隔</font></font></h3>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>disable-monitoring-lock</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 如果设置为，</font><font style="vertical-align: inherit;">则不适用</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，因为监控锁告诉 Gatus 一次仅评估一个端点。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了确保 Gatus 提供可靠且准确的结果（即响应时间），Gatus 一次仅评估一个端点。换句话说，即使您有多个具有相同间隔的端点，它们也不会同时执行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过运行 Gatus 来自行测试，其中多个端点配置了非常短、不切实际的间隔（例如 1 毫秒）。您会注意到响应时间不会波动 - 这是因为当在不同的 goroutine 上评估端点时，有一个全局锁可以防止多个端点同时运行。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不幸的是，有一个缺点。如果您有很多端点，包括一些非常慢或容易超时的端点（默认超时为 10 秒），那么这意味着在请求的整个持续时间内，无法评估其他端点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该间隔不包括请求本身的持续时间，这意味着如果端点的间隔为 30 秒，而请求需要 2 秒才能完成，则两次评估之间的时间戳将为 32 秒，而不是 30 秒。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然这不会阻止 Gatus 对所有其他端点执行运行状况检查，但可能会导致 Gatus 无法遵守配置的时间间隔，例如：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点A间隔5s，10s后超时完成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点B间隔5s，需要1ms完成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点 B 将无法每 5 秒运行一次，因为端点 A 的健康评估时间比其间隔时间长</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总而言之，虽然 Gatus 可以处理您向其设置的任何间隔，但您最好以较高的间隔处理较慢的请求。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据经验，我个人将更复杂的运行状况检查的间隔设置为</font></font><code>5m</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（5 分钟），将用于警报的简单运行状况检查（PagerDuty/Twilio）设置为</font></font><code>30s</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-default-timeouts" class="anchor" aria-hidden="true" tabindex="-1" href="#default-timeouts"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认超时</font></font></h3>
<table>
<thead>
<tr>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点类型</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">暂停</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HTTP协议</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10秒</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">传输控制协议</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10秒</font></font></td>
</tr>
<tr>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ICMP</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10秒</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要修改超时，请参阅</font></font><a href="#client-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">客户端配置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-a-tcp-endpoint" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-a-tcp-endpoint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 TCP 端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过添加前缀</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>tcp:\\</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在非常基本的级别上监视 TCP 端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">redis</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>tcp://127.0.0.1:6379<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: redis
    url: &quot;tcp://127.0.0.1:6379&quot;
    interval: 30s
    conditions:
      - &quot;[CONNECTED] == true&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TCP 端点不支持</font><font style="vertical-align: inherit;">占位符</font></font><code>[STATUS]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及字段</font></font><code>endpoints[].body</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font><font style="vertical-align: inherit;">、 和</font></font><code>endpoints[].headers</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><code>endpoints[].method</code><font style="vertical-align: inherit;"></font><code>endpoints[].graphql</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这适用于数据库（Postgres、MySQL 等）和缓存（Redis、Memcached 等）等应用程序。</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝</font></font><code>[CONNECTED] == true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不保证端点本身是健康的 - 它只保证给定地址处有某些东西正在侦听给定端口，并且已成功建立与该地址的连接。</font></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-a-udp-endpoint" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-a-udp-endpoint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 UDP 端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过添加前缀</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>udp:\\</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在非常基本的级别上监视 UDP 端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>udp://example.org:80<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example
    url: &quot;udp://example.org:80&quot;
    conditions:
      - &quot;[CONNECTED] == true&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">UDP 端点不支持</font><font style="vertical-align: inherit;">占位符</font></font><code>[STATUS]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及字段 、</font></font><code>endpoints[].body</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font><font style="vertical-align: inherit;">和</font></font><code>endpoints[].headers</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><code>endpoints[].method</code><font style="vertical-align: inherit;"></font><code>endpoints[].graphql</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这适用于基于 UDP 的应用程序。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-a-sctp-endpoint" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-a-sctp-endpoint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 SCTP 端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过添加前缀</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>sctp:\\</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在非常基本的级别上监视流控制传输协议（SCTP）端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>sctp://127.0.0.1:38412<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example
    url: &quot;sctp://127.0.0.1:38412&quot;
    conditions:
      - &quot;[CONNECTED] == true&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SCTP 端点不支持</font><font style="vertical-align: inherit;">占位符</font></font><code>[STATUS]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以及字段</font></font><code>endpoints[].body</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font><font style="vertical-align: inherit;">、 和</font></font><code>endpoints[].headers</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。
</font></font><code>endpoints[].method</code><font style="vertical-align: inherit;"></font><code>endpoints[].graphql</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这适用于基于 SCTP 的应用程序。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-a-websocket-endpoint" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-a-websocket-endpoint"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控 WebSocket 端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过使用</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>ws://</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前缀</font></font><code>wss://</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您可以在非常基本的级别上监视 WebSocket 端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>wss://example.com/<span class="pl-pds">"</span></span>
    <span class="pl-ent">body</span>: <span class="pl-s"><span class="pl-pds">"</span>status<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].result &gt;= 0<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example
    url: &quot;wss://example.com/&quot;
    body: &quot;status&quot;
    conditions:
      - &quot;[CONNECTED] == true&quot;
      - &quot;[BODY].result >= 0&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">符包含查询的输出，并</font></font><code>[CONNECTED]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
显示连接是否已成功建立。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-an-endpoint-using-icmp" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-an-endpoint-using-icmp"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 ICMP 监控端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过添加前缀</font></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><code>icmp:\\</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 ICMP（或更常见的“ping”或“echo”）在非常基本的级别上监视端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">ping-example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>icmp://example.com<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: ping-example
    url: &quot;icmp://example.com&quot;
    conditions:
      - &quot;[CONNECTED] == true&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ICMP 类型的端点仅</font><font style="vertical-align: inherit;">支持占位符</font></font><code>[CONNECTED]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>[IP]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和。</font></font><code>[RESPONSE_TIME]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以指定前缀为 的域</font></font><code>icmp://</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或前缀为 的 IP 地址</font></font><code>icmp://</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
如果您在 Linux 上运行 Gatus，如果遇到任何问题，请阅读</font></font><a href="https://github.com/prometheus-community/pro-bing#linux"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/prometheus-community/pro-bing#linux</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上的 Linux 部分。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-an-endpoint-using-dns-queries" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-an-endpoint-using-dns-queries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 DNS 查询监控端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>dns</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在端点中</font><font style="vertical-align: inherit;">定义配置会自动将所述端点标记为 DNS 类型的端点：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">example-dns-query</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>8.8.8.8<span class="pl-pds">"</span></span> <span class="pl-c"><span class="pl-c">#</span> Address of the DNS server to use</span>
    <span class="pl-ent">dns</span>:
      <span class="pl-ent">query-name</span>: <span class="pl-s"><span class="pl-pds">"</span>example.com<span class="pl-pds">"</span></span>
      <span class="pl-ent">query-type</span>: <span class="pl-s"><span class="pl-pds">"</span>A<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY] == 93.184.216.34<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[DNS_RCODE] == NOERROR<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: example-dns-query
    url: &quot;8.8.8.8&quot; # Address of the DNS server to use
    dns:
      query-name: &quot;example.com&quot;
      query-type: &quot;A&quot;
    conditions:
      - &quot;[BODY] == 93.184.216.34&quot;
      - &quot;[DNS_RCODE] == NOERROR&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有两个占位符可用于 DNS 类型端点的条件：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符</font></font><code>[BODY]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析为查询的输出。例如，类型的查询</font></font><code>A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将返回 IPv4。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符解析</font></font><code>[DNS_RCODE]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为与查询返回的响应代码关联的名称，例如
</font></font><code>NOERROR</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>FORMERR</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>SERVFAIL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>NXDOMAIN</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等。</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-an-endpoint-using-ssh" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-an-endpoint-using-ssh"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SSH 监控端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>endpoints[].url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用 SSH 通过添加前缀来</font><font style="vertical-align: inherit;">监视端点</font></font><code>ssh:\\</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">ssh-example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>ssh://example.com:22<span class="pl-pds">"</span></span> <span class="pl-c"><span class="pl-c">#</span> port is optional. Default is 22.</span>
    <span class="pl-ent">ssh</span>:
      <span class="pl-ent">username</span>: <span class="pl-s"><span class="pl-pds">"</span>username<span class="pl-pds">"</span></span>
      <span class="pl-ent">password</span>: <span class="pl-s"><span class="pl-pds">"</span>password<span class="pl-pds">"</span></span>
    <span class="pl-ent">body</span>: <span class="pl-s">|</span>
<span class="pl-s">      {</span>
<span class="pl-s">        "command": "uptime"</span>
<span class="pl-s">      }</span>
<span class="pl-s"></span>    <span class="pl-ent">interval</span>: <span class="pl-c1">1m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 0<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: ssh-example
    url: &quot;ssh://example.com:22&quot; # port is optional. Default is 22.
    ssh:
      username: &quot;username&quot;
      password: &quot;password&quot;
    body: |
      {
        &quot;command&quot;: &quot;uptime&quot;
      }
    interval: 1m
    conditions:
      - &quot;[CONNECTED] == true&quot;
      - &quot;[STATUS] == 0&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSH 类型的端点支持以下占位符：</font></font></p>
<ul dir="auto">
<li><code>[CONNECTED]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">判断</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SSH 连接是否成功，</font></font><code>false</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">否则</font></font></li>
<li><code>[STATUS]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解析在远程服务器上执行的命令的退出代码（例如</font></font><code>0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">成功）</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-an-endpoint-using-starttls" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-an-endpoint-using-starttls"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 STARTTLS 监控端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想要确保没有问题的电子邮件服务器，通过 STARTTLS 对其进行监控将作为一个很好的初始指标：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">starttls-smtp-example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>starttls://smtp.gmail.com:587<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30m</span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">timeout</span>: <span class="pl-c1">5s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 48h<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: starttls-smtp-example
    url: &quot;starttls://smtp.gmail.com:587&quot;
    interval: 30m
    client:
      timeout: 5s
    conditions:
      - &quot;[CONNECTED] == true&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 48h&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-an-endpoint-using-tls" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-an-endpoint-using-tls"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 TLS 监控端点</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 SSL/TLS 加密（例如基于 TLS 的 LDAP）监控端点可以帮助检测证书过期：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">tls-ldaps-example</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>tls://ldap.example.com:636<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">30m</span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">timeout</span>: <span class="pl-c1">5s</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[CONNECTED] == true<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 48h<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: tls-ldaps-example
    url: &quot;tls://ldap.example.com:636&quot;
    interval: 30m
    client:
      timeout: 5s
    conditions:
      - &quot;[CONNECTED] == true&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 48h&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-monitoring-domain-expiration" class="anchor" aria-hidden="true" tabindex="-1" href="#monitoring-domain-expiration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">监控域名过期</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用占位符监控除 DNS 之外的所有端点类型的域的过期情况</font></font><code>[DOMAIN_EXPIRATION]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">check-domain-and-certificate-expiration</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">1h</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[DOMAIN_EXPIRATION] &gt; 720h<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[CERTIFICATE_EXPIRATION] &gt; 240h<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: check-domain-and-certificate-expiration
    url: &quot;https://example.org&quot;
    interval: 1h
    conditions:
      - &quot;[DOMAIN_EXPIRATION] > 720h&quot;
      - &quot;[CERTIFICATE_EXPIRATION] > 240h&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠ 占位符的使用要求Gatus</font><a href="https://github.com/TwiN/whois"><font style="vertical-align: inherit;">通过库</font></a></font><code>[DOMAIN_EXPIRATION]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向官方 IANA WHOIS 服务发送请求</font><font style="vertical-align: inherit;">
，并且在某些情况下，向特定于 TLD 的 WHOIS 服务器发送辅助请求（例如</font><font style="vertical-align: inherit;">）。为了防止 WHOIS 服务在您发送过多请求时限制您的 IP 地址，Gatus 将阻止您</font><font style="vertical-align: inherit;">在间隔小于 的终端节点上使用占位符</font><font style="vertical-align: inherit;">。</font></font><a href="https://github.com/TwiN/whois"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>whois.nic.sh</code><font style="vertical-align: inherit;"></font><code>[DOMAIN_EXPIRATION]</code><font style="vertical-align: inherit;"></font><code>5m</code><font style="vertical-align: inherit;"></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-disable-monitoring-lock" class="anchor" aria-hidden="true" tabindex="-1" href="#disable-monitoring-lock"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">禁用监控锁定</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font><code>disable-monitoring-lock</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表示可以同时监控多个端点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然此行为通常不会有害，但使用</font></font><code>[RESPONSE_TIME]</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">占位符的条件可能会受到同时评估多个端点的影响，因此，此参数的默认值为</font></font><code>false</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能想要禁用监控锁的三个主要原因：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您正在使用 Gatus 进行负载测试（每个端点都会在不同的 goroutine 上定期评估，因此从技术上讲，如果您以 1 秒的间隔创建 100 个端点，Gatus 将每秒发送 100 个请求）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您有</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">很多</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点需要监控</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您想要以非常短的时间间隔（&lt; 5s）测试多个端点</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-reloading-configuration-on-the-fly" class="anchor" aria-hidden="true" tabindex="-1" href="#reloading-configuration-on-the-fly"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">即时重新加载配置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了方便起见，如果在 Gatus 运行时更新加载的配置文件，Gatus 会自动动态重新加载配置。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>skip-invalid-config-update</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，如果更新配置无效，应用程序将退出，但您可以通过设置为</font><font style="vertical-align: inherit;">来将 Gatus 配置为在配置文件更新为无效配置时继续运行</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请记住，在 Gatus 运行时，通过查看日志并确保没有看到以下消息，在每次对配置文件应用更新后确保配置文件的有效性符合您的最佳利益：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>The configuration file was updated, but it is not valid. The old configuration will continue being used.
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="The configuration file was updated, but it is not valid. The old configuration will continue being used." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果不这样做，无论出于何种原因重新启动应用程序，Gatus 都可能无法启动。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我建议不要设置</font></font><code>skip-invalid-config-update</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以</font></font><code>true</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">避免此类情况，但选择权在于您。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您不使用文件存储</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则在 Gatus 运行时更新配置实际上与重新启动应用程序相同。</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📝 如果绑定的是配置文件而不是配置文件夹，则可能无法检测到更新。参见</font></font><a href="https://github.com/TwiN/gatus/issues/151" data-hovercard-type="issue" data-hovercard-url="/TwiN/gatus/issues/151/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#151</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<h3 tabindex="-1" dir="auto"><a id="user-content-endpoint-groups" class="anchor" aria-hidden="true" tabindex="-1" href="#endpoint-groups"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点组</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">端点组用于将仪表板上的多个端点分组在一起。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">frontend</span>
    <span class="pl-ent">group</span>: <span class="pl-s">core</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">backend</span>
    <span class="pl-ent">group</span>: <span class="pl-s">core</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">monitoring</span>
    <span class="pl-ent">group</span>: <span class="pl-s">internal</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">nas</span>
    <span class="pl-ent">group</span>: <span class="pl-s">internal</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">random endpoint that is not part of a group</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org/<span class="pl-pds">"</span></span>
    <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: frontend
    group: core
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;

  - name: backend
    group: core
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;

  - name: monitoring
    group: internal
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;

  - name: nas
    group: internal
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;

  - name: random endpoint that is not part of a group
    url: &quot;https://example.org/&quot;
    interval: 5m
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上面的配置将产生如下所示的仪表板：</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/endpoint-groups.png"><img src="/TwiN/gatus/raw/master/.github/assets/endpoint-groups.png" alt="Gatus 端点组" style="max-width: 100%;"></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-exposing-gatus-on-a-custom-path" class="anchor" aria-hidden="true" tabindex="-1" href="#exposing-gatus-on-a-custom-path"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在自定义路径上公开 Gatus</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目前，您可以使用完全限定域名 (FQDN)（例如</font></font><code>status.example.org</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.但是，它不支持基于路径的路由，这意味着您无法通过像</font></font><code>example.org/status/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关更多信息，请参阅</font></font><a class="issue-link js-issue-link" data-error-text="Failed to load title" data-id="812779780" data-permission-text="Title is private" data-url="https://github.com/TwiN/gatus/issues/88" data-hovercard-type="issue" data-hovercard-url="/TwiN/gatus/issues/88/hovercard" href="https://github.com/TwiN/gatus/issues/88"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#88</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-exposing-gatus-on-a-custom-port" class="anchor" aria-hidden="true" tabindex="-1" href="#exposing-gatus-on-a-custom-port"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在自定义端口上公开 Gatus</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，Gatus 暴露在 port 上</font></font><code>8080</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但您可以通过设置参数指定不同的端口</font></font><code>web.port</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">web</span>:
  <span class="pl-ent">port</span>: <span class="pl-c1">8081</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="web:
  port: 8081" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用的是像 Heroku 这样的 PaaS，它不允许您设置自定义端口并通过环境变量公开它，那么您可以直接在配置文件中使用该环境变量：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">web</span>:
  <span class="pl-ent">port</span>: <span class="pl-s">${PORT}</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="web:
  port: ${PORT}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-configuring-a-startup-delay" class="anchor" aria-hidden="true" tabindex="-1" href="#configuring-a-startup-delay"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置启动延迟</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果出于任何原因，您需要 Gatus 在监视应用程序启动时的端点之前等待给定的时间，则可以使用</font></font><code>GATUS_DELAY_START_SECONDS</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境变量使 Gatus 在启动时休眠。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-keeping-your-configuration-small" class="anchor" aria-hidden="true" tabindex="-1" href="#keeping-your-configuration-small"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保持较小的配置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然不是特定于 Gatus，但您可以利用 YAML 锚点来创建默认配置。如果您有一个很大的配置文件，这应该可以帮助您保持干净。</font></font></p>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></summary>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">default-endpoint</span>: <span class="pl-s">&amp;defaults</span>
  <span class="pl-ent">group</span>: <span class="pl-s">core</span>
  <span class="pl-ent">interval</span>: <span class="pl-c1">5m</span>
  <span class="pl-ent">client</span>:
    <span class="pl-ent">insecure</span>: <span class="pl-c1">true</span>
    <span class="pl-ent">timeout</span>: <span class="pl-c1">30s</span>
  <span class="pl-ent">conditions</span>:
    - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>

<span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">anchor-example-1</span>
    <span class="pl-ent">&lt;&lt;</span>: <span class="pl-s">*defaults               </span><span class="pl-c"><span class="pl-c">#</span> This will merge the configuration under &amp;defaults with this endpoint</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.org<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">anchor-example-2</span>
    <span class="pl-ent">&lt;&lt;</span>: <span class="pl-s">*defaults</span>
    <span class="pl-ent">group</span>: <span class="pl-s">example              </span><span class="pl-c"><span class="pl-c">#</span> This will override the group defined in &amp;defaults</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://example.com<span class="pl-pds">"</span></span>

  - <span class="pl-ent">name</span>: <span class="pl-s">anchor-example-3</span>
    <span class="pl-ent">&lt;&lt;</span>: <span class="pl-s">*defaults</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">conditions</span>:                <span class="pl-c"><span class="pl-c">#</span> This will override the conditions defined in &amp;defaults</span>
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span>
      - <span class="pl-s"><span class="pl-pds">"</span>[BODY].status == UP<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="default-endpoint: &amp;defaults
  group: core
  interval: 5m
  client:
    insecure: true
    timeout: 30s
  conditions:
    - &quot;[STATUS] == 200&quot;

endpoints:
  - name: anchor-example-1
    <<: *defaults               # This will merge the configuration under &amp;defaults with this endpoint
    url: &quot;https://example.org&quot;

  - name: anchor-example-2
    <<: *defaults
    group: example              # This will override the group defined in &amp;defaults
    url: &quot;https://example.com&quot;

  - name: anchor-example-3
    <<: *defaults
    url: &quot;https://twin.sh/health&quot;
    conditions:                # This will override the conditions defined in &amp;defaults
      - &quot;[STATUS] == 200&quot;
      - &quot;[BODY].status == UP&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</details>
<h3 tabindex="-1" dir="auto"><a id="user-content-proxy-client-configuration" class="anchor" aria-hidden="true" tabindex="-1" href="#proxy-client-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理客户端配置</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>proxy-url</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以通过在客户端配置中</font><font style="vertical-align: inherit;">设置参数来配置客户端使用的代理。</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">endpoints</span>:
  - <span class="pl-ent">name</span>: <span class="pl-s">website</span>
    <span class="pl-ent">url</span>: <span class="pl-s"><span class="pl-pds">"</span>https://twin.sh/health<span class="pl-pds">"</span></span>
    <span class="pl-ent">client</span>:
      <span class="pl-ent">proxy-url</span>: <span class="pl-s">http://proxy.example.com:8080</span>
    <span class="pl-ent">conditions</span>:
      - <span class="pl-s"><span class="pl-pds">"</span>[STATUS] == 200<span class="pl-pds">"</span></span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
  - name: website
    url: &quot;https://twin.sh/health&quot;
    client:
      proxy-url: http://proxy.example.com:8080
    conditions:
      - &quot;[STATUS] == 200&quot;" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-how-to-fix-431-request-header-fields-too-large-error" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-fix-431-request-header-fields-too-large-error"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何修复 431 请求标头字段太大错误</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据您的环境部署位置以及 Gatus 前面的中间件或反向代理的类型，您可能会遇到此问题。这可能是因为请求标头太大，例如大cookie。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认情况下，</font></font><code>web.read-buffer-size</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置为</font></font><code>8192</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但像这样增加该值将增加读取缓冲区大小：</font></font></p>
<div class="highlight highlight-source-yaml notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-ent">web</span>:
  <span class="pl-ent">read-buffer-size</span>: <span class="pl-c1">32768</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="web:
  read-buffer-size: 32768" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-badges" class="anchor" aria-hidden="true" tabindex="-1" href="#badges"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">徽章</font></font></h3>
<h4 tabindex="-1" dir="auto"><a id="user-content-uptime" class="anchor" aria-hidden="true" tabindex="-1" href="#uptime"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正常运行时间</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/3b91555add58c3d53643fe202fadac9149ef034c03b29b87423fbef134f06f6e/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f31682f62616467652e737667"><img src="https://camo.githubusercontent.com/3b91555add58c3d53643fe202fadac9149ef034c03b29b87423fbef134f06f6e/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f31682f62616467652e737667" alt="正常运行时间1小时" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/1h/badge.svg" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/23b6a77d2b7a202e367bc253b99b94646523c8b05183a41896911239a500fae0/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f3234682f62616467652e737667"><img src="https://camo.githubusercontent.com/23b6a77d2b7a202e367bc253b99b94646523c8b05183a41896911239a500fae0/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f3234682f62616467652e737667" alt="正常运行时间 24 小时" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/24h/badge.svg" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/288b204a02deb21b3bf01adc37b5513315877973944162c87c901b89c6990316/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f37642f62616467652e737667"><img src="https://camo.githubusercontent.com/288b204a02deb21b3bf01adc37b5513315877973944162c87c901b89c6990316/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f757074696d65732f37642f62616467652e737667" alt="正常运行时间7天" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/7d/badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus 可以为您的受监控端点之一自动生成 SVG 徽章。这允许您将徽章放入各个应用程序的自述文件中，甚至根据需要创建您自己的状态页面。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成徽章的路径如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/{key}/uptimes/{duration}/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/{key}/uptimes/{duration}/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在哪里：</font></font></p>
<ul dir="auto">
<li><code>{duration}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>7d</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>24h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>1h</code></li>
<li><code>{key}</code><font style="vertical-align: inherit;"></font><code>&lt;GROUP_NAME&gt;_&lt;ENDPOINT_NAME&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有其中两个变量都具有</font></font><code> </code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>_</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>,</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换</font></font><code>.</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 的</font><font style="vertical-align: inherit;">模式</font></font><code>-</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您想要</font></font><code>frontend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组中端点过去 24 小时内的正常运行时间</font></font><code>core</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则 URL 将如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>https://example.com/api/v1/endpoints/core_frontend/uptimes/7d/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="https://example.com/api/v1/endpoints/core_frontend/uptimes/7d/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果要显示不属于组的端点，则必须将组值留空：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>https://example.com/api/v1/endpoints/_frontend/uptimes/7d/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="https://example.com/api/v1/endpoints/_frontend/uptimes/7d/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>![Uptime 24h](https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/24h/badge.svg)
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="![Uptime 24h](https://status.twin.sh/api/v1/endpoints/core_blog-external/uptimes/24h/badge.svg)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想查看每个可用徽章的视觉示例，只需导航到端点的详细信息页面即可。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-health" class="anchor" aria-hidden="true" tabindex="-1" href="#health"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">健康</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d30244bb4f246e38d43f710e7c270bc9bc8e88207e5252793d596a1c0bdb37a8/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f6865616c74682f62616467652e737667"><img src="https://camo.githubusercontent.com/d30244bb4f246e38d43f710e7c270bc9bc8e88207e5252793d596a1c0bdb37a8/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f6865616c74682f62616467652e737667" alt="健康" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/health/badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成徽章的路径如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/{key}/health/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/{key}/health/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在哪里：</font></font></p>
<ul dir="auto">
<li><code>{key}</code><font style="vertical-align: inherit;"></font><code>&lt;GROUP_NAME&gt;_&lt;ENDPOINT_NAME&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有其中两个变量都具有</font></font><code> </code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>_</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>,</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换</font></font><code>.</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 的</font><font style="vertical-align: inherit;">模式</font></font><code>-</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您想要</font></font><code>frontend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组中端点的当前状态</font></font><code>core</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则 URL 将如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>https://example.com/api/v1/endpoints/core_frontend/health/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="https://example.com/api/v1/endpoints/core_frontend/health/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-health-shieldsio" class="anchor" aria-hidden="true" tabindex="-1" href="#health-shieldsio"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">健康 (Shields.io)</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/cd7461479835a31ca5ab079a4aa5ca6a59fa5567a0d67769f8c688febbebbfdd/68747470733a2f2f696d672e736869656c64732e696f2f656e64706f696e743f75726c3d68747470732533412532462532467374617475732e7477696e2e73682532466170692532467631253246656e64706f696e7473253246636f72655f626c6f672d65787465726e616c2532466865616c746825324662616467652e736869656c6473"><img src="https://camo.githubusercontent.com/cd7461479835a31ca5ab079a4aa5ca6a59fa5567a0d67769f8c688febbebbfdd/68747470733a2f2f696d672e736869656c64732e696f2f656e64706f696e743f75726c3d68747470732533412532462532467374617475732e7477696e2e73682532466170692532467631253246656e64706f696e7473253246636f72655f626c6f672d65787465726e616c2532466865616c746825324662616467652e736869656c6473" alt="健康" data-canonical-src="https://img.shields.io/endpoint?url=https%3A%2F%2Fstatus.twin.sh%2Fapi%2Fv1%2Fendpoints%2Fcore_blog-external%2Fhealth%2Fbadge.shields" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成徽章的路径如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/{key}/health/badge.shields
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/{key}/health/badge.shields" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在哪里：</font></font></p>
<ul dir="auto">
<li><code>{key}</code><font style="vertical-align: inherit;"></font><code>&lt;GROUP_NAME&gt;_&lt;ENDPOINT_NAME&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有其中两个变量都具有</font></font><code> </code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>_</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>,</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换</font></font><code>.</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 的</font><font style="vertical-align: inherit;">模式</font></font><code>-</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例如，如果您想要</font></font><code>frontend</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组中端点的当前状态</font></font><code>core</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则 URL 将如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>https://example.com/api/v1/endpoints/core_frontend/health/badge.shields
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="https://example.com/api/v1/endpoints/core_frontend/health/badge.shields" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://shields.io/badges/endpoint-badge" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看有关 Shields.io 徽章端点的更多信息</font><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-response-time" class="anchor" aria-hidden="true" tabindex="-1" href="#response-time"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应时间</font></font></h4>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/d2216a682ff03ab3cc94c9f12604548cdc59b9cb08f3d363e8d9fc7cf2ecebcb/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f31682f62616467652e737667"><img src="https://camo.githubusercontent.com/d2216a682ff03ab3cc94c9f12604548cdc59b9cb08f3d363e8d9fc7cf2ecebcb/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f31682f62616467652e737667" alt="响应时间1小时" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/response-times/1h/badge.svg" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/005f146a3c088615ab3b34243a2ca42263bbedae69a9b40477f11eb55fae9b1f/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f3234682f62616467652e737667"><img src="https://camo.githubusercontent.com/005f146a3c088615ab3b34243a2ca42263bbedae69a9b40477f11eb55fae9b1f/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f3234682f62616467652e737667" alt="响应时间24小时" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/response-times/24h/badge.svg" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/234e0b88150d7b58e24b3ffaa074afba89fd7b7bbd0dc38f99d3cabfb28071f2/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f37642f62616467652e737667"><img src="https://camo.githubusercontent.com/234e0b88150d7b58e24b3ffaa074afba89fd7b7bbd0dc38f99d3cabfb28071f2/68747470733a2f2f7374617475732e7477696e2e73682f6170692f76312f656e64706f696e74732f636f72655f626c6f672d65787465726e616c2f726573706f6e73652d74696d65732f37642f62616467652e737667" alt="响应时间7天" data-canonical-src="https://status.twin.sh/api/v1/endpoints/core_blog-external/response-times/7d/badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成徽章的端点如下：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/{key}/response-times/{duration}/badge.svg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/{key}/response-times/{duration}/badge.svg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在哪里：</font></font></p>
<ul dir="auto">
<li><code>{duration}</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是</font></font><code>7d</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><code>24h</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>1h</code></li>
<li><code>{key}</code><font style="vertical-align: inherit;"></font><code>&lt;GROUP_NAME&gt;_&lt;ENDPOINT_NAME&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有其中两个变量都具有</font></font><code> </code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>_</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>,</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">替换</font></font><code>.</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 的</font><font style="vertical-align: inherit;">模式</font></font><code>-</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<h5 tabindex="-1" dir="auto"><a id="user-content-how-to-change-the-color-thresholds-of-the-response-time-badge" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-change-the-color-thresholds-of-the-response-time-badge"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何更改响应时间徽章的颜色阈值</font></font></h5>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要更改响应时间标志的阈值，可以将相应的配置添加到端点。数组中的值对应于级别 [Awesome、Great、Good、Passable、Bad] 所有五个值必须以毫秒 (ms) 为单位。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>endpoints:
- name: nas
  group: internal
  url: "https://example.org/"
  interval: 5m
  conditions:
    - "[STATUS] == 200"
  ui:
    badge:
      response-time:
        thresholds: [550, 850, 1350, 1650, 1750]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="endpoints:
- name: nas
  group: internal
  url: &quot;https://example.org/&quot;
  interval: 5m
  conditions:
    - &quot;[STATUS] == 200&quot;
  ui:
    badge:
      response-time:
        thresholds: [550, 850, 1350, 1650, 1750]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-api" class="anchor" aria-hidden="true" tabindex="-1" href="#api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序编程接口</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gatus 提供了一个简单的只读 API，可以查询该 API，以便以编程方式确定端点状态和历史记录。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有端点都可以通过向以下端点发出 GET 请求来获得：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/statuses
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/statuses" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例： https: </font></font><a href="https://status.twin.sh/api/v1/endpoints/statuses" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">//status.twin.sh/api/v1/endpoints/statuses</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">还可以使用以下模式查询特定端点：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>/api/v1/endpoints/{group}_{endpoint}/statuses
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="/api/v1/endpoints/{group}_{endpoint}/statuses" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例：</font></font><a href="https://status.twin.sh/api/v1/endpoints/core_blog-home/statuses" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://status.twin.sh/api/v1/endpoints/core_blog-home/statuses</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>Accept-Encoding</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果HTTP 标头包含</font><font style="vertical-align: inherit;">.gzip 压缩，则将使用 Gzip 压缩</font></font><code>gzip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 将返回一个 JSON 负载，</font></font><code>Content-Type</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">响应标头设置为</font></font><code>application/json</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.查询 API 不需要这样的标头。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-installing-as-binary" class="anchor" aria-hidden="true" tabindex="-1" href="#installing-as-binary"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">作为二进制安装</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以使用以下命令将 Gatus 下载为二进制文件：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>go install github.com/TwiN/gatus/v5@latest
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="go install github.com/TwiN/gatus/v5@latest" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-high-level-design-overview" class="anchor" aria-hidden="true" tabindex="-1" href="#high-level-design-overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高层设计概述</font></font></h3>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/TwiN/gatus/blob/master/.github/assets/gatus-diagram.jpg"><img src="/TwiN/gatus/raw/master/.github/assets/gatus-diagram.jpg" alt="伽图斯图" style="max-width: 100%;"></a></p>
</article></div>

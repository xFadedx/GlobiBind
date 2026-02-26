<h1 align="center">🎧 SpotiBind [Works on Free & Premium]</h1>

<p align="center">
  <strong>Lightweight Windows desktop app for controlling Spotify with fully customizable global keyboard shortcuts.</strong>
</p>

<p align="center">
  No need to alt-tab.<br>
  Control playback from anywhere.
</p>

<hr>

<h2 align="center">📚 Quick Navigation</h2>

<p align="center">
  <a href="#features">✨ Features</a> •
  <a href="#free-vs-premium">🆓 Free vs Premium</a> •
  <a href="#how-it-works">🖥️ How It Works</a> •
  <a href="#premium-setup-guide">🔧 Premium Setup</a> •
  <a href="#optional-features">⚙️ Optional Features</a> •
  <a href="#security-notes">🛡️ Security</a>
</p>

<hr>

<h2 id="features">✨ Features</h2>

<ul>
  <li>🔓 Works instantly on <strong>Free Spotify accounts</strong> (No login required)</li>
  <li>🔐 Secure Spotify API authentication (Premium optional)</li>
  <li>⌨️ Fully customizable global hotkeys</li>
  <li>▶ Play / Pause</li>
  <li>⏭ Next Track</li>
  <li>⏮ Previous Track</li>
  <li>🔊 Volume Up</li>
  <li>🔉 Volume Down</li>
  <li>🎵 Show Current Song</li>
  <li>🔄 Reconnect support</li>
</ul>

<hr>

<h2 id="free-vs-premium">🆓 Free vs Premium</h2>

<p><strong>Free Spotify Users:</strong></p>
<ul>
  <li>No login required</li>
  <li>No Spotify Developer setup needed</li>
  <li>All playback hotkeys work instantly</li>
</ul>

<p><strong>Premium Spotify Users:</strong></p>
<ul>
  <li>Optional Spotify login via Developer API</li>
  <li>🔔 Song toast notifications</li>
  <li><small>Displays the currently playing song in the bottom right corner of your screen</small></li>
</ul>

<hr>

<h2 id="how-it-works">🖥️ How It Works</h2>

<p>
SpotiBind uses system-level media controls to interact directly with the Spotify desktop app.
</p>

<p>
For Premium users, it can optionally connect to the Spotify Web API using your own developer credentials to enable enhanced features like song notifications.
</p>

<hr>

<h2 id="premium-setup-guide">🔧 Premium Setup Guide (Optional)</h2>

<h3>1️⃣ Create a Spotify Developer App</h3>

<ol>
  <li>
    Go to:
    👉 <a href="https://developer.spotify.com/dashboard" target="_blank">
    https://developer.spotify.com/dashboard
    </a>
  </li>
  <li>Log in with your Spotify account.</li>
  <li>Click <strong>"Create App"</strong></li>
  <li>
    Fill in:
    <ul>
      <li><strong>App Name:</strong> SpotiBind</li>
      <li><strong>Description:</strong> Spotify hotkey controller</li>
      <li><strong>Redirect URI:</strong><br>
      <code>http://127.0.0.1:8888/callback</code></li>
    </ul>
  </li>
  <li>Save the app.</li>
</ol>

<hr>

<h3>2️⃣ Get Your Credentials</h3>

<ul>
  <li>Copy your <strong>Client ID</strong></li>
  <li>Click <strong>"Show Client Secret"</strong> and copy it</li>
</ul>

<hr>

<h3>3️⃣ Configure SpotiBind</h3>

<ol>
  <li>Open <strong>SpotiBind → Settings</strong></li>
  <li>Enter your Client ID and Client Secret</li>
  <li>Click <strong>Connect to Spotify</strong></li>
</ol>

<p>
Authorize access in your browser.
</p>

<p>
Once authorized, SpotiBind will show <strong>Connected</strong>.
</p>

<hr>

<h2>⌨️ Setting Up Hotkeys</h2>

<ol>
  <li>Click the hotkey field next to any action.</li>
  <li>Press your desired key combination.</li>
  <li><strong>Done!</strong></li>
</ol>

<p>
Hotkeys are global — they work anywhere in Windows.
</p>

<hr>

<h2 id="optional-features">⚙️ Optional Features</h2>

<ul>
  <li>🚀 Start with Windows</li>
  <li>🧩 Minimize to System Tray on Close</li>
  <li>🔔 Song Toast Notifications <small>[Premium Feature]</small></li>
</ul>

<hr>

<h2 id="security-notes">🛡️ Security Notes</h2>

<ul>
  <li>Your Client Secret stays on your machine.</li>
  <li>SpotiBind does not store Spotify passwords.</li>
  <li>Authentication uses Spotify's official OAuth flow.</li>
</ul>

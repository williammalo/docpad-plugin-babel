<!-- TITLE/ -->

<h1>docpad-plugin-babel</h1>

<!-- /TITLE -->


<!-- BADGES/ -->

<span class="badge-travisci"><a href="http://travis-ci.com/docpad/docpad-plugin-babel" title="Check this project's build status on TravisCI"><img src="https://img.shields.io/travis/com/docpad/docpad-plugin-babel/master.svg" alt="Travis CI Build Status" /></a></span>
<span class="badge-npmversion"><a href="https://npmjs.org/package/docpad-plugin-babel" title="View this project on NPM"><img src="https://img.shields.io/npm/v/docpad-plugin-babel.svg" alt="NPM version" /></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/docpad-plugin-babel" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/docpad-plugin-babel.svg" alt="NPM downloads" /></a></span>
<span class="badge-daviddm"><a href="https://david-dm.org/docpad/docpad-plugin-babel" title="View the status of this project's dependencies on DavidDM"><img src="https://img.shields.io/david/docpad/docpad-plugin-babel.svg" alt="Dependency Status" /></a></span>
<span class="badge-daviddmdev"><a href="https://david-dm.org/docpad/docpad-plugin-babel#info=devDependencies" title="View the status of this project's development dependencies on DavidDM"><img src="https://img.shields.io/david/dev/docpad/docpad-plugin-babel.svg" alt="Dev Dependency Status" /></a></span>
<br class="badge-separator" />
<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-flattr"><a href="https://flattr.com/profile/balupton" title="Donate to this project using Flattr"><img src="https://img.shields.io/badge/flattr-donate-yellow.svg" alt="Flattr donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-wishlist"><a href="https://bevry.me/wishlist" title="Buy an item on our wishlist for us"><img src="https://img.shields.io/badge/wishlist-donate-yellow.svg" alt="Wishlist browse button" /></a></span>

<!-- /BADGES -->


<!-- DESCRIPTION/ -->

DocPad plugin to compile es-next to es5 using babel

<!-- /DESCRIPTION -->


Compiles es-next into es5 with [babel](http://babeljs.io)

Convention: `.js.babel`

## Usage

### Common Errors

-   ERROR: **`require is not defined`** error when using ES6 `import` statements:
-   This is fixed easily with the [docplad-plugin-browserifydocs](https://github.com/docpad/docpad-plugin-browserifydocs) plugin:
    -   `docpad install browserifydocs`
    -   Add this to the top of your `.js.babel` file :
        ```
        ---
        browserify: true
        ---
        ```

<!-- INSTALL/ -->

<h2>Install</h2>

Install this DocPad plugin by entering <code>docpad install babel</code> into your terminal.

<!-- /INSTALL -->


<!-- HISTORY/ -->

<h2>History</h2>

<a href="https://github.com/docpad/docpad-plugin-babel/blob/master/HISTORY.md#files">Discover the release history by heading on over to the <code>HISTORY.md</code> file.</a>

<!-- /HISTORY -->


<!-- CONTRIBUTE/ -->

<h2>Contribute</h2>

<a href="https://github.com/docpad/docpad-plugin-babel/blob/master/CONTRIBUTING.md#files">Discover how you can contribute by heading on over to the <code>CONTRIBUTING.md</code> file.</a>

<!-- /CONTRIBUTE -->


<!-- BACKERS/ -->

<h2>Backers</h2>

<h3>Maintainers</h3>

These amazing people are maintaining this project:

<ul><li><a href="maloweb.com">William Malo</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=williammalo" title="View the GitHub contributions of William Malo on repository docpad/docpad-plugin-babel">view contributions</a></li></ul>

<h3>Sponsors</h3>

No sponsors yet! Will you be the first?

<span class="badge-githubsponsors"><a href="https://github.com/sponsors/balupton" title="Donate to this project using GitHub Sponsors"><img src="https://img.shields.io/badge/github-donate-yellow.svg" alt="GitHub Sponsors donate button" /></a></span>
<span class="badge-patreon"><a href="https://patreon.com/bevry" title="Donate to this project using Patreon"><img src="https://img.shields.io/badge/patreon-donate-yellow.svg" alt="Patreon donate button" /></a></span>
<span class="badge-flattr"><a href="https://flattr.com/profile/balupton" title="Donate to this project using Flattr"><img src="https://img.shields.io/badge/flattr-donate-yellow.svg" alt="Flattr donate button" /></a></span>
<span class="badge-liberapay"><a href="https://liberapay.com/bevry" title="Donate to this project using Liberapay"><img src="https://img.shields.io/badge/liberapay-donate-yellow.svg" alt="Liberapay donate button" /></a></span>
<span class="badge-buymeacoffee"><a href="https://buymeacoffee.com/balupton" title="Donate to this project using Buy Me A Coffee"><img src="https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg" alt="Buy Me A Coffee donate button" /></a></span>
<span class="badge-opencollective"><a href="https://opencollective.com/bevry" title="Donate to this project using Open Collective"><img src="https://img.shields.io/badge/open%20collective-donate-yellow.svg" alt="Open Collective donate button" /></a></span>
<span class="badge-crypto"><a href="https://bevry.me/crypto" title="Donate to this project using Cryptocurrency"><img src="https://img.shields.io/badge/crypto-donate-yellow.svg" alt="crypto donate button" /></a></span>
<span class="badge-paypal"><a href="https://bevry.me/paypal" title="Donate to this project using Paypal"><img src="https://img.shields.io/badge/paypal-donate-yellow.svg" alt="PayPal donate button" /></a></span>
<span class="badge-wishlist"><a href="https://bevry.me/wishlist" title="Buy an item on our wishlist for us"><img src="https://img.shields.io/badge/wishlist-donate-yellow.svg" alt="Wishlist browse button" /></a></span>

<h3>Contributors</h3>

These amazing people have contributed code to this project:

<ul><li><a href="https://github.com/balupton">Benjamin Lupton</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=balupton" title="View the GitHub contributions of Benjamin Lupton on repository docpad/docpad-plugin-babel">view contributions</a></li>
<li><a href="https://github.com/danguilherme">Guilherme Ventura</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=danguilherme" title="View the GitHub contributions of Guilherme Ventura on repository docpad/docpad-plugin-babel">view contributions</a></li>
<li><a href="http://jimmyking.me">Jimmy King</a></li>
<li><a href="https://github.com/mikeumus">Michael Duane Mooring</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=mikeumus" title="View the GitHub contributions of Michael Duane Mooring on repository docpad/docpad-plugin-babel">view contributions</a></li>
<li><a href="http://mikeum.us">Michael Duane Mooring</a></li>
<li><a href="https://github.com/sdomagala">Sebastian Domagala</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=sdomagala" title="View the GitHub contributions of Sebastian Domagala on repository docpad/docpad-plugin-babel">view contributions</a></li>
<li><a href="maloweb.com">William Malo</a> — <a href="https://github.com/docpad/docpad-plugin-babel/commits?author=williammalo" title="View the GitHub contributions of William Malo on repository docpad/docpad-plugin-babel">view contributions</a></li></ul>

<a href="https://github.com/docpad/docpad-plugin-babel/blob/master/CONTRIBUTING.md#files">Discover how you can contribute by heading on over to the <code>CONTRIBUTING.md</code> file.</a>

<!-- /BACKERS -->


<!-- LICENSE/ -->

<h2>License</h2>

Unless stated otherwise all works are:

<ul><li>Copyright &copy; <a href="maloweb.com">William Malo</a></li></ul>

and licensed under:

<ul><li><a href="http://spdx.org/licenses/MIT.html">MIT License</a></li></ul>

<!-- /LICENSE -->

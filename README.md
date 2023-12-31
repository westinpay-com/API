# API
# Automatic payment documentation with WestinPay Wallet

<img src="https://westinpay.com/assets/images/20BC661C-3C34-4C9B-BAAD-D7BE95162806.jpeg" >
<img src="https://westinpay.com/assets/images/AFCF2D90-B4A4-4710-8B12-B420F7ECB07F.jpeg" >

# API
Automatic payment documentation with WestinPay Wallet
<div class="doc-body">
                        <div class="doc-section" id="introduction-section">
                            <div class="doc-content">
                                <section id="introduction">
                                    <h3>Introduction</h3>
                                    <p class="mt-2">This section describes the <strong>WestinPay</strong>
                                        payment gateway API.                                    </p>
                                    <hr>
                                    <p class="text-justify">
                                        <strong>WestinPay</strong> API is easy to implement in your business software. Our API is well formatted URLs, accepts cURL requests, returns JSON responses.                                    </p>
                                    <p class="text-justify">
                                        You can use the API in test mode, which does not affect your live data. The API key is use to authenticate the request and determines the request is valid payment or not. For test mode just use the sandbox URL and In case of live mode use the live URL from  section <a href="#initiate">Initiate Payment</a> .
                                    </p>
                                </section>
                            </div><!-- doc-content end -->
                        </div><!-- doc-section end -->
                        <div class="doc-section" id="currency">
                            <div class="doc-content">
                                <section id="">
                                    <h2>Supported Currencies</h2>
                                    <p class="mt-2">This section describes the currencies supported by <strong>WestinPay</strong></p>
                                    <hr>
                                    <p>
                                        <strong>WestinPay</strong>
                                         allows to make transaction with below currencies. Any new currency may update in future.                                    </p>
                                </section>
                                <section id="setting-two">
                                    <div class="table-responsive">
                                        <table class="table table-bordered">
                                            <thead>
                                                <tr>
                                                    <th>Currency Name</th>
                                                    <th>Currency Symbol</th>
                                                    <th>Currency Code</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                                                                    <tr>
                                                        <td>United States Dollar</td>
                                                        <td>$</td>
                                                        <td>USD</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>GBP</td>
                                                        <td>£</td>
                                                        <td>GBP</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Euro</td>
                                                        <td>€</td>
                                                        <td>EUR</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Canadian dollar</td>
                                                        <td>CAD</td>
                                                        <td>CAD</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Swiss franc</td>
                                                        <td>CHF</td>
                                                        <td>CHF</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Australian dollar</td>
                                                        <td>A$</td>
                                                        <td>AUD</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Hong Kong dollar</td>
                                                        <td>HK$</td>
                                                        <td>HKD</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Indian rupee</td>
                                                        <td>₹</td>
                                                        <td>INR</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>New Zealand dollar</td>
                                                        <td>NZ$</td>
                                                        <td>NZD</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Russian ruble</td>
                                                        <td>₽</td>
                                                        <td>RUB</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Romanian leu</td>
                                                        <td>L</td>
                                                        <td>RON</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Bulgarian lev</td>
                                                        <td>BGN</td>
                                                        <td>BGN</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Swedish krona</td>
                                                        <td>kr</td>
                                                        <td>SEK</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Turkish lira</td>
                                                        <td>₺</td>
                                                        <td>TRY</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Brazilian real</td>
                                                        <td>R$</td>
                                                        <td>BRL</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Polonya zlotisi</td>
                                                        <td>zł</td>
                                                        <td>PLN</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>South Africa ZAR</td>
                                                        <td>R</td>
                                                        <td>ZAR</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>Bitcoin</td>
                                                        <td>₿</td>
                                                        <td>BTC</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>ETHEREUM</td>
                                                        <td>Ξ</td>
                                                        <td>ETH</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>DOGECOİN</td>
                                                        <td>Ð</td>
                                                        <td>DOGE</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>AZN MANAT</td>
                                                        <td>₼</td>
                                                        <td>AZN</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>TRX</td>
                                                        <td>TRX</td>
                                                        <td>TRX</td>
                                                    </tr>
                                                                                                    <tr>
                                                        <td>USDT.TRC20</td>
                                                        <td>₮</td>
                                                        <td>USDT</td>
                                                    </tr>
                                                                                            </tbody>
                                        </table>
                                    </div><!-- table-responsive end -->
                                </section>
                            </div><!-- doc-content end -->
                        </div><!-- doc-section end -->
                        <div class="doc-section" id="api-key">
                            <div class="doc-content">
                                <section id="">
                                    <h2>Get The Api Key</h2>
                                    <p class="mt-2">This section describes how you can get your api key.</p>
                                    <hr>
                                    <p class="text-justify">Login to your <strong>WestinPay</strong> merchant account. If you don't have any ? <a target="_blank" href=" https://westinpay.com/merchant "> https://westinpay.com/merchant</a>
                                    </p>
                                    <p>Next step is to find the <span class="text--base">Api Key</span>
                                        menu in your dashboard sidebar. Click the menu.                                    </p>
                                    <p class="text-justify">The api keys can be found there which is <strong>Public key and Secret key.</strong>
                                        Use these keys to initiate the API request. Every time you can generate new API key by clicking                                        <span class="text--base">Generate Api Key</span>
                                        button. Remember do not share these keys with anyone.                                    </p>
                                </section>
                            </div><!-- doc-content end -->
                        </div><!-- doc-section end -->
                        <div class="doc-section" id="initiate">
                            <div class="doc-content">
                                <section id="">
                                    <h2>Initiate Payment</h2>
                                    <p class="mt-2">This section describes the process of initaiing the payment.</p>
                                    <hr>
                                    <p>
                                        To initiate the payment follow the example code and be careful with the perameters. You will need to make request with these following API end points.                                    </p>
                                    <p>
                                        <strong>Live End Point:</strong>
                                        <span class="text--base"> https://westinpay.com/payment/initiate </span>
                                    </p>
                                    <p class="d-flex align-items-center flex-wrap gap-2">
                                        <strong>Test End Point:</strong>
                                        <span class="text--base responsive-text"> https://westinpay.com/sandbox/payment/initiate </span>
                                    </p>
                                    <p>
                                        <strong>Test Mode Mail:</strong>
                                        <span class="text--base">test_mode@mail.com</span>
                                    </p>
                                    <p>
                                        <strong>Test Mode Verification Code:</strong>
                                        <span class="text--base">222666</span>
                                    </p>
                                    <p>
                                        <strong>Request Method:</strong>
                                        <span class="text--base">POST</span>
                                    </p>
                                </section>
                                <section id="setting-two">
                                    <p>Request to the end point with the following parameters below.</p>
                                    <div class="table-responsive">
                                        <table class="table table-bordered">
                                            <thead>
                                                <tr>
                                                    <th>Param Name</th>
                                                    <th>Param Type</th>
                                                    <th>Description</th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                <tr>
                                                    <td>public_key</td>
                                                    <td>string (50)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Your Public API key                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>identifier</td>
                                                    <td>string (20)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Identifier is basically for identify payment at your end                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>currency</td>
                                                    <td>string (4)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Currency Code, Must be in Upper Case. e.g. USD,EUR                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>amount</td>
                                                    <td>decimal</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment amount.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>details</td>
                                                    <td>string (100)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Details of your payment or transaction.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>ipn_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        The url of instant payment notification.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>success_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment success redirect url.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>cancel_url</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Payment cancel redirect url.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>site_logo</td>
                                                    <td>string/url</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Your business site logo.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>checkout_theme</td>
                                                    <td>string</td>
                                                    <td>
                                                        <span class="badge badge--info font-size--12px">Optional</span>
                                                        Checkout form theme dark/light. Default theme is light                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>customer_name</td>
                                                    <td>string (30)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Customer name.                                                    </td>
                                                </tr>
                                                <tr>
                                                    <td>customer_email</td>
                                                    <td>string (30)</td>
                                                    <td>
                                                        <span class="badge badge--danger font-size--12px">Required</span>
                                                        Customer valid email.                                                    </td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div><!-- table-responsive end -->

                

<pre><code class="language-php" id="php">&lt;?php
    $parameters = [
        'identifier' =&gt; 'DFU80XZIKS',
        'currency' =&gt; 'USD',
        'amount' =&gt; 100.00,
        'details' =&gt; 'Purchase T-shirt',
        'ipn_url' =&gt; 'http://example.com/ipn_url.php',
        'cancel_url' =&gt; 'http://example.com/cancel_url.php',
        'success_url' =&gt; 'http://example.com/success_url.php',
        'public_key' =&gt; 'your_public_key',
        'site_logo' =&gt; 'https://westinpay.com/assets/images/logoIcon/logo.png',
        'checkout_theme' =&gt; 'dark',
        'customer_name' =&gt; 'John Doe',
        'customer_email' =&gt; 'john@mail.com',

    ];

    //live end point
    $url = "https://westinpay.com/payment/initiate";

    //test end point
    $url = "https://westinpay.com/sandbox/payment/initiate";

    $ch = curl_init();
    curl_setopt($ch, CURLOPT_SSL_VERIFYHOST, false);
    curl_setopt($ch, CURLOPT_URL, $url);
    curl_setopt($ch, CURLOPT_POSTFIELDS,  $parameters);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
    $result = curl_exec($ch);
    curl_close($ch);

    //$result contains the response back.
?&gt;</code></pre>

                              

<pre><code class="language-php" id="response">//Error Response.
{
    "error": "true",
    "message": "Invalid api key"
}

//Success Response.
{
    "success": "ok",
    "message": "Payment Initiated. Redirect to url.",
    "url":"http://example.com/initiate/payment/checkout?payment_id=eJSAASDxdrt4DASDASVNASJA7893232432cvmdsamnvASF"
}
</code></pre>

                                
 <div class="doc-code">
                                <div class="doc-code-inner">
                                    <div class="code-block">
                                   
                                       

<pre><code class="language-php" id="php">&lt;?php
    $parameters = [
        'identifier' =&gt; 'DFU80XZIKS',
        'currency' =&gt; 'USD',
        'amount' =&gt; 100.00,
        'details' =&gt; 'Purchase T-shirt',
        'ipn_url' =&gt; 'http://example.com/ipn_url.php',
        'cancel_url' =&gt; 'http://example.com/cancel_url.php',
        'success_url' =&gt; 'http://example.com/success_url.php',
        'public_key' =&gt; 'your_public_key',
        'site_logo' =&gt; 'https://westinpay.com/assets/images/logoIcon/logo.png',
        'checkout_theme' =&gt; 'dark',
        'customer_name' =&gt; 'John Doe',
        'customer_email' =&gt; 'john@mail.com',

    ];

    //live end point
    $url = "https://westinpay.com/payment/initiate";

    //test end point
    $url = "https://westinpay.com/sandbox/payment/initiate";

    $ch = curl_init();
    curl_setopt($ch, CURLOPT_SSL_VERIFYHOST, false);
    curl_setopt($ch, CURLOPT_URL, $url);
    curl_setopt($ch, CURLOPT_POSTFIELDS,  $parameters);
    curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
    $result = curl_exec($ch);
    curl_close($ch);

    //$result contains the response back.
?&gt;</code></pre>

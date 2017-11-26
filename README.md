# Vebitcoin Tickers API documentation

Vebitcoin Coin instant API document

## Usage

You can add and use the api address you want to use in the system main url address.

System main url address: https://www.vebitcoin.com
Sample api address: / Ticker / Btc
Example usage: https://www.vebitcoin.com/Ticker/Btc

## Request Limits

* .../Ticker/... requests are limited to 10 requests per 100 miliseconds.
* Other requests are limited to 1 request per 100 miliseconds.
* If you make more than 60 consequent unauthorized requests your IP address will be blocked.


## Ticker BTC

<code>GET</code> .../Ticker/Btc

**Result:**
``` json
{
Last: 37716.84,
High: 38303.14,
Low: 35659.84,
Vwap: 37037.64,
Volume: 32.6852999,
Bid: 37648.45,
Ask: 37716.84,
Time: "2017-11-26T13:29:26.21",
Open: 37268.57
}
```
* Last: Last BTC price.
* High: Last 24 hours price high.
* Low: Last 24 hours price low.
* Vwap: Last 24 hours volume weighted average price.
* Volume: Last 24 hours volume.
* Bid: Highest buy order.
* Ask: Lowest sell order.
* Time: Unix timestamp date and time.
* Open : First price of the day.

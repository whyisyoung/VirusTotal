# VirusTotal
This repository contains the dataset of the "Main Experiment" for the paper:

> Peng Peng, Limin Yang, Linhai Song, Gang Wang. 2019. Opening the Blackbox of VirusTotal: Analyzing Online Phishing Scan Engines. In Internet Measurement Conference (IMC ’19), October 21–23, 2019, Amsterdam, Netherlands.

There are 36 files (18 PayPal + 18 IRS), each represents the network requests the phishing site received. 

For each file, each line contains a network request in the following format:

`Timestamp	IP	visited URL`



Table of domains and targeting phishing brand:

| Server index | domain                                                 | phishing brand |
| ------------ | ------------------------------------------------------ | -------------- |
| Server-01    | gfvelz52ffug3o0pj22w4olkx6wlp0mn0ptx93609vx2cz856b.xyz | PayPal         |
| Server-02    | 8gxysxkkyfjq4jsrhef0bjx4ofvpzks361f6k0tybnxd9ixwx8.xyz | IRS            |
| Server-03    | rp8nqp0j2yvw5bj5gidizkmuxhi1vmgjo19bgo305mc9oz7xi3.xyz | PayPal         |
| Server-04    | 6s1eu09dvidzy1rjega60fgx6i1fhgldoepjcgfkxfdcwxxl08.xyz | IRS            |
| Server-05    | ttvfuj6tqwm2prhcmz56n7jl2lp8k5nrxvmen8ey1oxtwrv06r.xyz | PayPal         |
| Server-06    | ag3ic652q72jsi51hhtawz0s5yyhbzul2ih5odec2f0cbilg83.xyz | IRS            |
| Server-07    | dtzyfgkbv14vek0afw9o4jzfjexbz858c2mue9w3ql857mgv54.xyz | PayPal         |
| Server-08    | asl1fv60q71w5jx3w2xuisfeipc4qb5rot48asis1pcnd0kpb4.xyz | IRS            |
| Server-09    | kqv6rafp86mxhq6vv8sj3m0z60onylwaf9a2tohjohrh2htu7g.xyz | PayPal         |
| Server-10    | invi9qigvl1lq2lp9foi8197bnrwauaq91c8n5vhr6mxl8nl7c.xyz | IRS            |
| Server-11    | ywa4qhb0i3lvb5u9gkmr36mwmzgxquyep496szftjx1se26xiz.xyz | PayPal         |
| Server-12    | 4xvyp9cauhozgg2izluwt8xwp8gtfawihhsszgpigekpn1tlce.xyz | IRS            |
| Server-13    | 1po8gtd1lq393q6b3lt0p8ouaftquo9jaw1m8pz9w7zxping7r.xyz | PayPal         |
| Server-14    | 4mhmmd3g69uaxgtxcwvkz4lsjtyjxw0mat3dzoqeqi68pw9438.xyz | IRS            |
| Server-15    | 5xer3xxkojsi3s414ydwcl6eyffr57g1fhbuju7b1oilpyupjs.xyz | PayPal         |
| Server-16    | mlqmjq4a8okayca2wyqd57g2ie6dk6i4i2kvwwlywre0lkjssp.xyz | IRS            |
| Server-17    | f1s88nnlyncxvl6zlfh6zon7b42l97fcwuqw1ueravnnakh8xh.xyz | PayPal         |
| Server-18    | 37qfnywtb827pmr8uhmt3xe6emsjcnpoo8msl2bp3s2zhy69gf.xyz | IRS            |
| Server-19    | dgd23xf53y9rg7m1vum2ts7l0bt3kv75a7kcc5ottxfx9d9wvr.xyz | PayPal         |
| Server-20    | 8yv0q2tg2e822683ekiwyhcspyd2sgs6s9go7ynw226t6zobuq.xyz | IRS            |
| Server-21    | mnhu8evd9rqax8uauoqnldqrlyazxc14f0xqav9ow385ek1d23.xyz | PayPal         |
| Server-22    | f1usynp3buv8y45d1taowsejwy07h8v8jaunjb75qmajjzmuda.xyz | IRS            |
| Server-23    | 0w6dcfry8540pw57cy436t1by8qqd2cen2mmf31fv9betkpxb0.xyz | PayPal         |
| Server-24    | vdi81f1gnp6qdueyywshrxnhxv2mg2ndv1manedfbarv7a4fyn.xyz | IRS            |
| Server-25    | fvntg1d17veb3y7j0j0iceq5gtyjbewa5c6c3f60czqrw0p7ah.xyz | PayPal         |
| Server-26    | vixrrrl4213cny36r84fyik7ze7527p4f4ma9mizwl39x6dmf3.xyz | IRS            |
| Server-27    | 63wiittfkh02hwyziv2kxs7m6b1vkrd76ltk34bnanq28rbfjb.xyz | PayPal         |
| Server-28    | s9u6dfszc35whjfh6dnkec12at7be0w1y8ojmjcsa611k1b77c.xyz | IRS            |
| Server-29    | 9u5syataewpmftpqy85di8eqxmudypq5ksuizcmmbgc0bcaqxa.xyz | PayPal         |
| Server-30    | uoqyup35k51yfcjpxfv6yj393f5jzl5g8xsh49n7pw7jqvetxk.xyz | IRS            |
| Server-31    | 86g6pcwh2dlogtn950mc7zxpd6lgexwyj5d38s7ahmmtauuwkt.xyz | PayPal         |
| Server-32    | wh9ukfofbs1jsso95f1nis9tvcuccivf7uiih62kwsfnujg7cb.xyz | IRS            |
| Server-33    | noob8p0ukhgv77xnm18wwvd7kuikvuu2qzgtfo64nv8dehr6ys.xyz | PayPal         |
| Server-34    | gsgi56vbeo8qpeha3v8mbxe6q3bu17ipqjn0c5kr9gf6puts0s.xyz | IRS            |
| Server-35    | fse30tnp6p0ewtru05fcc3g04qlneyz4hl9lbz0nl6jqqtubz1.xyz | PayPal         |
| Server-36    | r11fvi4b9s59fato50mcbd3b1pk5q7l2mvgahcnedwzaongnlv.xyz | IRS            |

Note: Even though we informed Digital Ocean to not to block our phishing site, 5 of the phishing sites (Server-17, 21, 23, 24, 25) were blacklisted by Namesilo. Server-21, 23, 25 were blacklisted on 03/25/2019, Server-17 were blacklisted on 04/05/2019, and Server-24 were blacklisted on 04/08/2019. That's why these 5 phishing sites do not have all the four-week network requests.



If you have any questions, please contact Limin (liminy2@illinois.edu).


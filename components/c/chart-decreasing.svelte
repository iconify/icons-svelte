<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i38fRbR)" class="lnj_5hbwv"/><path fill="url(#iaaOy3f)" class="lnj_5hbwv"/><path fill="url(#iovnFlu)" class="lnj_5hbwv"/><path fill="url(#ipZrYgY)" class="lnj_5hbwv"/><path fill="url(#ibrD3hm)" class="lnj_5hbwv"/><path fill="url(#iDkIWHb)" class="lnj_5hbwv"/><path fill="url(#iCSNlPe)" class="lnj_5hbwv"/><path fill="url(#iI7G30d)" class="lnj_5hbwv"/><path fill="url(#ifD5ZOg)" class="lnj_5hbwv"/><path fill="url(#iW4hL9d)" class="lnj_5hbwv"/><path fill="url(#iydKPOd)" class="lnj_5hbwv"/><path fill="url(#iofUqwc)" class="lnj_5hbwv"/><path fill="url(#ifc7zBe)" class="lnj_5hbwv"/><path fill="url(#iy1Ww0d)" class="lnj_5hbwv"/><path fill="url(#irMvYlc)" class="lnj_5hbwv"/><path fill="url(#iv0Mpvc)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#ipxxIGb)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iaaOy3f)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#i6xgYMs)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iQpzkrc)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iuuerze)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#ipZrYgY)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#icgsm5c)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#ix4qiep)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#ibrD3hm)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iLwb4De)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iKOGOIb)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iJ0g6Eb)" clip-rule="evenodd" class="x06lcpb1c"/><path fill="url(#iODrjLc)" class="r2hxidb8z"/><path fill="url(#itkXLae)" class="r2hxidb8z"/><path fill="url(#iumYjke)" class="r2hxidb8z"/><path fill="url(#iDOEfqR)" class="r2hxidb8z"/><path fill="url(#i5sHXld)" class="r2hxidb8z"/><path fill="url(#iOFBLre)" class="r2hxidb8z"/><path fill="url(#iewpQIe)" class="z7-5qzbzd"/><path fill="url(#ivaEOlc)" class="z7-5qzbzd"/><path fill="url(#iDN2E7b)" class="sa_nz4b8n"/><path fill="url(#i6TJrOc)" class="c17d5tbqv"/><path fill="url(#iySgmrE)" class="r2hxidb8z"/><path fill="url(#iSKQ31c)" class="r2hxidb8z"/><path fill="url(#iQ7SVhe)" class="r2hxidb8z"/><path fill="url(#i8qZFvc)" class="r2hxidb8z"/><path fill="url(#iIL1Ftd)" class="r2hxidb8z"/><path fill="url(#iAi2Wxb)" class="c17d5tbqv"/><path fill="url(#iAhodrd)" class="c17d5tbqv"/><path fill="url(#izv7SSd)" class="sa_nz4b8n"/><path fill="url(#igm4zpb)" class="sa_nz4b8n"/><path fill="url(#iWjzddc)" class="sa_nz4b8n"/><path fill="url(#inWX5bd)" class="sa_nz4b8n"/><path fill="url(#iiCKD0e)" class="z5hhzpbhj"/><path fill="url(#iLBzZ0d)" class="z5hhzpbhj"/><path fill="url(#ikdUAZc)" class="k7yx54buf"/><path fill="url(#iZXTyee)" class="c17d5tbqv"/><path fill="url(#irQoGwb)" class="aw8jjvsbj"/><path fill="url(#iIQVVYb)" class="aw8jjvsbj"/><defs><radialGradient id="iovnFlu" cx="0" cy="0" r="1" gradientTransform="matrix(-6.33301 -8.43386 4.71248 -3.53861 22.114 28.58)" gradientUnits="userSpaceOnUse"><stop offset=".849" class="tx-ejek8w"/><stop offset=".992" class="u0v84ib2i"/></radialGradient><radialGradient id="ibrD3hm" cx="0" cy="0" r="1" gradientTransform="rotate(93.468 -1.237 18.32)scale(1.91441)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="aurukqv7b"/><stop offset=".711" class="k_o10mkpl"/><stop offset=".883" class="uftqaobui"/><stop offset="1" class="dnwuz_5hb"/></radialGradient><radialGradient id="iDkIWHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0725 1.2344 -2.58537 2.2463 19.14 19.878)" gradientUnits="userSpaceOnUse"><stop class="aurukqv7b"/><stop offset=".711" class="k_o10mkpl"/><stop offset=".883" class="uftqaobui"/><stop offset="1" class="dnwuz_5hb"/></radialGradient><radialGradient id="iCSNlPe" cx="0" cy="0" r="1" gradientTransform="rotate(159.392 7.99 9.501)scale(4.3805)" gradientUnits="userSpaceOnUse"><stop offset=".577" class="zqqjoby9b"/><stop offset=".863" class="b1kqsxs2k"/><stop offset=".992" class="yb2s_2bki"/></radialGradient><radialGradient id="iI7G30d" cx="0" cy="0" r="1" gradientTransform="rotate(64.252 4.845 12.122)scale(16.3731 11.7951)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="uyh48sl0l"/><stop offset="1" class="u0v84ib2i"/></radialGradient><radialGradient id="iy1Ww0d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.58858 .20883 -.81418 -21.7886 29.953 16.395)" gradientUnits="userSpaceOnUse"><stop class="x4aqjrs3p"/><stop offset="1" class="nfy4fkukk"/></radialGradient><radialGradient id="irMvYlc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.69009 3.2723 -3.38707 -3.81951 29.586 2.888)" gradientUnits="userSpaceOnUse"><stop class="iar3vjb-g"/><stop offset="1" class="vdus3ubud"/></radialGradient><radialGradient id="i6xgYMs" cx="0" cy="0" r="1" gradientTransform="rotate(-89.318 24.473 3.3)scale(4.71548)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="ny3yfgb0o"/><stop offset="1" class="zopk7hfod"/></radialGradient><radialGradient id="icgsm5c" cx="0" cy="0" r="1" gradientTransform="rotate(46.153 -3.95 16.861)scale(5.91528 5.28673)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="av2-vqbow"/><stop offset="1" class="n2kyu5b6a"/></radialGradient><radialGradient id="ix4qiep" cx="0" cy="0" r="1" gradientTransform="matrix(1.09034 1.23103 -2.57832 2.28365 19.432 19.856)" gradientUnits="userSpaceOnUse"><stop class="aurukqv7b"/><stop offset=".711" class="k_o10mkpl"/><stop offset=".883" class="uftqaobui"/><stop offset="1" class="dnwuz_5hb"/></radialGradient><radialGradient id="iLwb4De" cx="0" cy="0" r="1" gradientTransform="rotate(93.731 1.932 19.086)scale(1.86567 1.87938)" gradientUnits="userSpaceOnUse"><stop class="k1u4ibbzu"/><stop offset=".784" class="cx_4mdbij"/><stop offset="1" class="nfwn94blh"/></radialGradient><radialGradient id="iKOGOIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9176 .9176 -2.64761 -2.64761 22.483 19.523)" gradientUnits="userSpaceOnUse"><stop class="tz8zv0bkk"/><stop offset=".483" class="qm7qvmg_g"/><stop offset=".821" class="jlf-7kbch"/><stop offset="1" class="nfwn94blh"/></radialGradient><radialGradient id="iJ0g6Eb" cx="0" cy="0" r="1" gradientTransform="rotate(86.186 -1.955 19)scale(2.8757)" gradientUnits="userSpaceOnUse"><stop class="tz8zv0bkk"/><stop offset=".483" class="qm7qvmg_g"/><stop offset=".821" class="jlf-7kbch"/><stop offset="1" class="nfwn94blh"/></radialGradient><radialGradient id="i5sHXld" cx="0" cy="0" r="1" gradientTransform="rotate(-119.374 14.736 5.19)scale(7.15632 8.88299)" gradientUnits="userSpaceOnUse"><stop class="isldk1brm"/><stop offset=".525" class="j5ywl5v8k"/><stop offset="1" class="n0j5jidxu"/></radialGradient><radialGradient id="iySgmrE" cx="0" cy="0" r="1" gradientTransform="matrix(1.51975 2.04837 -2.5426 1.88644 20.012 17.567)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="sv2zlw2dn"/><stop offset=".736" class="amb-tebxd"/><stop offset="1" class="uflad7djn"/></radialGradient><radialGradient id="iSKQ31c" cx="0" cy="0" r="1" gradientTransform="matrix(2.99957 -.67446 .8372 3.7233 18.533 20.29)" gradientUnits="userSpaceOnUse"><stop offset=".397" class="sv2zlw2dn"/><stop offset=".736" class="amb-tebxd"/><stop offset="1" class="uflad7djn"/></radialGradient><radialGradient id="iQ7SVhe" cx="0" cy="0" r="1" gradientTransform="matrix(.32699 -1.36966 4.17757 .99734 16.876 21.698)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="ziha4-b7t"/><stop offset=".644" class="l5wq3hbzl"/><stop offset=".883" class="oqe73mbwe"/><stop offset="1" class="iljgn32hj"/></radialGradient><radialGradient id="i8qZFvc" cx="0" cy="0" r="1" gradientTransform="rotate(-117.122 15.625 5.4)scale(1.61864 4.93698)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="ziha4-b7t"/><stop offset=".644" class="l5wq3hbzl"/><stop offset=".883" class="oqe73mbwe"/><stop offset="1" class="iljgn32hj"/></radialGradient><radialGradient id="iIL1Ftd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1728 -1.23708 1.38133 -1.30955 19.655 20.834)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="vhateebqh"/><stop offset=".644" class="l3-a8cqpq"/><stop offset=".883" class="n0g19vblo"/><stop offset="1" class="f562pcs1g"/></radialGradient><radialGradient id="iAi2Wxb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90136 -1.30382 1.45584 -1.00646 20.556 19.84)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="vhateebqh"/><stop offset=".644" class="l3-a8cqpq"/><stop offset=".883" class="n0g19vblo"/><stop offset="1" class="f562pcs1g"/></radialGradient><radialGradient id="iAhodrd" cx="0" cy="0" r="1" gradientTransform="matrix(.11274 -1.29904 1.4505 .12589 21.1 19.225)" gradientUnits="userSpaceOnUse"><stop class="vhateebqh"/><stop offset=".644" class="l3-a8cqpq"/><stop offset=".883" class="n0g19vblo"/><stop offset="1" class="f562pcs1g"/></radialGradient><radialGradient id="izv7SSd" cx="0" cy="0" r="1" gradientTransform="rotate(119.894 5.847 15.332)scale(.70186 2.06233)" gradientUnits="userSpaceOnUse"><stop class="h225v4uku"/><stop offset=".173" class="s6ddwc0ky"/><stop offset=".426" class="ex_c1ub_z"/><stop offset=".619" class="viwln7b-c"/><stop offset=".806" class="ol0pg7b9v"/><stop offset="1" class="pe6lqzb_l"/></radialGradient><radialGradient id="igm4zpb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0134 .84503 -1.69115 -.02683 21.189 17.525)" gradientUnits="userSpaceOnUse"><stop class="smassabyb"/><stop offset=".173" class="s6ddwc0ky"/><stop offset=".426" class="ex_c1ub_z"/><stop offset=".609" class="viwln7b-c"/><stop offset=".806" class="ol0pg7b9v"/><stop offset="1" class="pe6lqzb_l"/></radialGradient><radialGradient id="iWjzddc" cx="0" cy="0" r="1" gradientTransform="matrix(.4805 .68799 -1.65325 1.15466 20.146 17.91)" gradientUnits="userSpaceOnUse"><stop class="o3pwfgfcy"/><stop offset=".173" class="suqznmn8o"/><stop offset=".426" class="u_gy5y8lq"/><stop offset=".619" class="s_fiwzb-w"/><stop offset=".806" class="llmh6e_ej"/><stop offset="1" class="hw_q97b9t"/></radialGradient><radialGradient id="inWX5bd" cx="0" cy="0" r="1" gradientTransform="matrix(.48288 .67066 -2.04167 1.47 18.788 19.04)" gradientUnits="userSpaceOnUse"><stop class="hq9d4hbub"/><stop offset=".173" class="kiq38nh4q"/><stop offset=".426" class="sm5_ixtig"/><stop offset=".619" class="if9qhibnt"/><stop offset=".806" class="jm4u9bxmz"/><stop offset="1" class="bahmhy1ts"/></radialGradient><radialGradient id="iiCKD0e" cx="0" cy="0" r="1" gradientTransform="rotate(-97.047 17.57 2.405)scale(.64373 1.07755)" gradientUnits="userSpaceOnUse"><stop class="wfn3ysb9g"/><stop offset=".173" class="hjo_h9biy"/><stop offset=".426" class="if5z9zbsw"/><stop offset=".619" class="rsujjy9lq"/><stop offset=".806" class="m8ui5fbqx"/><stop offset="1" class="vr3mtedyp"/></radialGradient><radialGradient id="iLBzZ0d" cx="0" cy="0" r="1" gradientTransform="matrix(-.33454 -.4845 1.20714 -.8335 18.177 19.778)" gradientUnits="userSpaceOnUse"><stop class="wfn3ysb9g"/><stop offset=".173" class="hjo_h9biy"/><stop offset=".426" class="if5z9zbsw"/><stop offset=".619" class="rsujjy9lq"/><stop offset=".806" class="m8ui5fbqx"/><stop offset="1" class="vr3mtedyp"/></radialGradient><radialGradient id="ikdUAZc" cx="0" cy="0" r="1" gradientTransform="matrix(.28851 -.69582 1.6051 .66553 16.461 19.83)" gradientUnits="userSpaceOnUse"><stop class="k77_omb-j"/><stop offset=".173" class="hjo_h9biy"/><stop offset=".426" class="if5z9zbsw"/><stop offset=".619" class="rsujjy9lq"/><stop offset=".806" class="m8ui5fbqx"/><stop offset="1" class="vr3mtedyp"/></radialGradient><radialGradient id="iZXTyee" cx="0" cy="0" r="1" gradientTransform="matrix(1.01968 .8906 -1.7471 2.0003 18.11 17.8)" gradientUnits="userSpaceOnUse"><stop class="od5pu1k7t"/><stop offset=".644" class="ctfngeewy"/><stop offset=".883" class="n1y3n3bir"/><stop offset="1" class="vw2hslbkg"/></radialGradient><radialGradient id="irQoGwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4407 1.80836 -4.29904 -1.04768 21.654 15.572)" gradientUnits="userSpaceOnUse"><stop class="c0a16t00w"/><stop offset=".644" class="m8ifh_wrs"/><stop offset=".883" class="cgmv-hfup"/><stop offset="1" class="yhew10btb"/></radialGradient><radialGradient id="iIQVVYb" cx="0" cy="0" r="1" gradientTransform="matrix(.66864 1.5956 -3.79328 1.58957 20.331 15.8)" gradientUnits="userSpaceOnUse"><stop class="mvouecbxe"/><stop offset=".644" class="z2r_7ybwh"/><stop offset=".883" class="lxyk3_bkx"/><stop offset="1" class="zg2cv7mfm"/></radialGradient><linearGradient id="i38fRbR" x1="27.125" x2="11.875" y1="3.875" y2="23.313" gradientUnits="userSpaceOnUse"><stop class="uyh48sl0l"/><stop offset="1" class="tx-ejek8w"/></linearGradient><linearGradient id="iaaOy3f" x1="9.738" x2="8.471" y1="14.307" y2="15.633" gradientUnits="userSpaceOnUse"><stop offset=".075" class="dnwuz_5hb"/><stop offset=".198" class="aurukqv7b"/><stop offset=".792" class="k_o10mkpl"/><stop offset="1" class="dnwuz_5hb"/></linearGradient><linearGradient id="ipZrYgY" x1="22.997" x2="21.663" y1="19.903" y2="21.236" gradientUnits="userSpaceOnUse"><stop offset=".075" class="dnwuz_5hb"/><stop offset=".198" class="aurukqv7b"/><stop offset=".792" class="k_o10mkpl"/><stop offset="1" class="dnwuz_5hb"/></linearGradient><linearGradient id="ifD5ZOg" x1="16" x2="16" y1="1.896" y2="4.36" gradientUnits="userSpaceOnUse"><stop class="z-_9w3ido"/><stop offset="1" class="elwkdipcw"/></linearGradient><linearGradient id="iW4hL9d" x1="16" x2="16" y1="1.014" y2="2.565" gradientUnits="userSpaceOnUse"><stop offset=".494" class="b9oyvne2s"/><stop offset=".797" class="apw2goc_s"/><stop offset="1" class="hm6m9s-po"/></linearGradient><linearGradient id="iydKPOd" x1="2.047" x2="5.066" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="ha165cbhx"/><stop offset=".696" class="fg7372sog"/><stop offset="1" class="cd1wm0_6r"/></linearGradient><linearGradient id="iofUqwc" x1="16" x2="16" y1="30.366" y2="26.42" gradientUnits="userSpaceOnUse"><stop class="ha165cbhx"/><stop offset="1" class="cd1wm0_6r"/></linearGradient><linearGradient id="ifc7zBe" x1="21.475" x2="21.475" y1="30.216" y2="27.918" gradientUnits="userSpaceOnUse"><stop class="zj8kg6brj"/><stop offset="1" class="jbzt1quqs"/></linearGradient><linearGradient id="iv0Mpvc" x1="16" x2="16" y1="4.359" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="av2-vqbow"/><stop offset="1" class="ny3yfgb0o"/></linearGradient><linearGradient id="ipxxIGb" x1="30.766" x2="26.953" y1="18.047" y2="18.047" gradientUnits="userSpaceOnUse"><stop class="vsb_wlbyi"/><stop offset="1" class="bnoc2wb_b"/></linearGradient><linearGradient id="iQpzkrc" x1="21.719" x2="21.719" y1="30.668" y2="27.187" gradientUnits="userSpaceOnUse"><stop class="h8su5dx7m"/><stop offset="1" class="nklmu6d-u"/></linearGradient><linearGradient id="iuuerze" x1="1.078" x2="6.391" y1="17.359" y2="17.359" gradientUnits="userSpaceOnUse"><stop class="lfsn49ywy"/><stop offset="1" class="c27919bru"/></linearGradient><linearGradient id="iODrjLc" x1="5.314" x2="27.922" y1="3.594" y2="23.172" gradientUnits="userSpaceOnUse"><stop class="j8dkrsils"/><stop offset="1" class="g3djntder"/></linearGradient><linearGradient id="itkXLae" x1="4.633" x2="2.643" y1="3.737" y2="7.5" gradientUnits="userSpaceOnUse"><stop offset=".42" class="o9htfcbhq"/><stop offset="1" class="difzc7ifv"/></linearGradient><linearGradient id="iumYjke" x1="10.144" x2="8.489" y1="12.488" y2="14.131" gradientUnits="userSpaceOnUse"><stop offset=".133" class="kpc6rq7ea"/><stop offset=".197" class="qzh-i3b7c"/><stop offset=".308" class="ewk22yt-x"/><stop offset=".381" class="ewk22yt-x"/><stop offset=".477" class="n9zk5l6un"/><stop offset=".576" class="kpc6rq7ea"/></linearGradient><linearGradient id="iDOEfqR" x1="27.542" x2="25.303" y1="21.594" y2="23.784" gradientUnits="userSpaceOnUse"><stop offset=".133" class="ya34kow3c"/><stop offset=".197" class="uubx54jqn"/><stop offset=".308" class="o0ofug0up"/><stop offset=".389" class="ylppfgxvv"/><stop offset=".492" class="bn79dunno"/><stop offset=".576" class="ya34kow3c"/></linearGradient><linearGradient id="iOFBLre" x1="8.226" x2="9.318" y1="14.122" y2="12.999" gradientUnits="userSpaceOnUse"><stop class="dp878dcfp"/><stop offset=".644" class="s_38r0bsq"/><stop offset=".792" class="znliez7ch"/><stop offset=".895" class="yul7fcj-a"/><stop offset="1" class="dsn6jiscq"/></linearGradient><linearGradient id="iewpQIe" x1="10.276" x2="9.451" y1="12.03" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="g_u6jvbpt"/><stop offset=".118" class="s88dor6kd"/><stop offset=".644" class="nkggduuyp"/><stop offset=".792" class="k1a1c-bnt"/><stop offset=".895" class="bxepnhmdp"/><stop offset="1" class="g_u6jvbpt"/></linearGradient><linearGradient id="ivaEOlc" x1="25.55" x2="24.749" y1="19.49" y2="20.348" gradientUnits="userSpaceOnUse"><stop class="omwnd69er"/><stop offset=".644" class="clr379cqy"/><stop offset=".792" class="m1796jbsw"/><stop offset=".895" class="g0zcx3tby"/><stop offset="1" class="aff6mimyr"/></linearGradient><linearGradient id="iDN2E7b" x1="31.248" x2="22.986" y1="27.558" y2="19.829" gradientUnits="userSpaceOnUse"><stop class="hpnswhhjk"/><stop offset="1" class="j32h0rq7l"/></linearGradient><linearGradient id="i6TJrOc" x1="23.519" x2="24.481" y1="21.369" y2="20.418" gradientUnits="userSpaceOnUse"><stop class="hdai0lb2z"/><stop offset=".151" class="qam2_0bmm"/><stop offset=".644" class="v-u69wa8p"/><stop offset=".792" class="n-wyv9crg"/><stop offset=".895" class="fofxpws0y"/><stop offset="1" class="hdai0lb2z"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:chart-decreasing" {...props}></Icon>
<style>
:global(.aff6mimyr) {
  stop-color: var(--svg-color--f95a99, #F95A99);
  stop-opacity: 0;
}

:global(.amb-tebxd) {
  stop-color: var(--svg-color--e53375, #E53375);
  stop-opacity: 0.595;
}

:global(.apw2goc_s) {
  stop-color: var(--svg-color--bababa, #BABABA);
  stop-opacity: 0.267;
}

:global(.aurukqv7b) {
  stop-color: var(--svg-color--988fb6, #988FB6);
}

:global(.av2-vqbow) {
  stop-color: var(--svg-color--c2bec6, #C2BEC6);
}

:global(.aw8jjvsbj) {
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.b1kqsxs2k) {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
  stop-opacity: 0.458;
}

:global(.b9oyvne2s) {
  stop-color: var(--svg-color--bababa, #BABABA);
}

:global(.bahmhy1ts) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0;
}

:global(.bn79dunno) {
  stop-color: var(--svg-color--fd5699, #FD5699);
  stop-opacity: 0.215;
}

:global(.bnoc2wb_b) {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
  stop-opacity: 0;
}

:global(.bxepnhmdp) {
  stop-color: var(--svg-color--f84e59, #F84E59);
  stop-opacity: 0.054;
}

:global(.c0a16t00w) {
  stop-color: var(--svg-color--d73d6f, #D73D6F);
}

:global(.c17d5tbqv) {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.c27919bru) {
  stop-color: var(--svg-color--96909c, #96909C);
  stop-opacity: 0;
}

:global(.cd1wm0_6r) {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
  stop-opacity: 0;
}

:global(.cgmv-hfup) {
  stop-color: var(--svg-color--d73d6f, #D73D6F);
  stop-opacity: 0.055;
}

:global(.clr379cqy) {
  stop-color: var(--svg-color--f95a99, #F95A99);
  stop-opacity: 0.265;
}

:global(.ctfngeewy) {
  stop-color: var(--svg-color--c74c64, #C74C64);
  stop-opacity: 0.265;
}

:global(.cx_4mdbij) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
  stop-opacity: 0.14;
}

:global(.difzc7ifv) {
  stop-color: var(--svg-color--fb545d, #FB545D);
  stop-opacity: 0;
}

:global(.dnwuz_5hb) {
  stop-color: var(--svg-color--988fb6, #988FB6);
  stop-opacity: 0;
}

:global(.dp878dcfp) {
  stop-color: var(--svg-color--c23240, #C23240);
}

:global(.dsn6jiscq) {
  stop-color: var(--svg-color--c23240, #C23240);
  stop-opacity: 0;
}

:global(.elwkdipcw) {
  stop-color: var(--svg-color--e0dfe2, #E0DFE2);
  stop-opacity: 0;
}

:global(.ewk22yt-x) {
  stop-color: var(--svg-color--f95a62, #F95A62);
}

:global(.ex_c1ub_z) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0.462;
}

:global(.f562pcs1g) {
  stop-color: var(--svg-color--d3296e, #D3296E);
  stop-opacity: 0;
}

:global(.fg7372sog) {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
  stop-opacity: 0.128;
}

:global(.fofxpws0y) {
  stop-color: var(--svg-color--c23274, #C23274);
  stop-opacity: 0.054;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g_u6jvbpt) {
  stop-color: var(--svg-color--f84e59, #F84E59);
  stop-opacity: 0;
}

:global(.g0zcx3tby) {
  stop-color: var(--svg-color--f95a99, #F95A99);
  stop-opacity: 0.054;
}

:global(.g3djntder) {
  stop-color: var(--svg-color--e12680, #E12680);
}

:global(.h225v4uku) {
  stop-color: var(--svg-color--fb5593, #FB5593);
}

:global(.h8su5dx7m) {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
}

:global(.ha165cbhx) {
  stop-color: var(--svg-color--b9b2bf, #B9B2BF);
}

:global(.hdai0lb2z) {
  stop-color: var(--svg-color--c23274, #C23274);
  stop-opacity: 0;
}

:global(.hjo_h9biy) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0.8;
}

:global(.hm6m9s-po) {
  stop-color: var(--svg-color--bababa, #BABABA);
  stop-opacity: 0;
}

:global(.hpnswhhjk) {
  stop-color: var(--svg-color--d8207b, #D8207B);
}

:global(.hq9d4hbub) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0.89;
}

:global(.hw_q97b9t) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0;
}

:global(.iar3vjb-g) {
  stop-color: var(--svg-color--f7f4f7, #F7F4F7);
}

:global(.if5z9zbsw) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0.462;
}

:global(.if9qhibnt) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0.215;
}

:global(.iljgn32hj) {
  stop-color: var(--svg-color--c92064, #C92064);
  stop-opacity: 0;
}

:global(.isldk1brm) {
  stop-color: var(--svg-color--d82667, #D82667);
}

:global(.j32h0rq7l) {
  stop-color: var(--svg-color--d8207b, #D8207B);
  stop-opacity: 0;
}

:global(.j5ywl5v8k) {
  stop-color: var(--svg-color--d32167, #D32167);
  stop-opacity: 0.59;
}

:global(.j8dkrsils) {
  stop-color: var(--svg-color--f74157, #F74157);
}

:global(.jbzt1quqs) {
  stop-color: var(--svg-color--cdbce0, #CDBCE0);
  stop-opacity: 0;
}

:global(.jlf-7kbch) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
  stop-opacity: 0.057;
}

:global(.jm4u9bxmz) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0.08;
}

:global(.k_o10mkpl) {
  stop-color: var(--svg-color--988fb6, #988FB6);
  stop-opacity: 0.141;
}

:global(.k1a1c-bnt) {
  stop-color: var(--svg-color--f84e59, #F84E59);
  stop-opacity: 0.134;
}

:global(.k1u4ibbzu) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
  stop-opacity: 0.78;
}

:global(.k77_omb-j) {
  stop-color: var(--svg-color--f4567d, #F4567D);
}

:global(.k7yx54buf) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.kiq38nh4q) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0.8;
}

:global(.kpc6rq7ea) {
  stop-color: var(--svg-color--f95a62, #F95A62);
  stop-opacity: 0;
}

:global(.l3-a8cqpq) {
  stop-color: var(--svg-color--d3296e, #D3296E);
  stop-opacity: 0.265;
}

:global(.l5wq3hbzl) {
  stop-color: var(--svg-color--c92064, #C92064);
  stop-opacity: 0.265;
}

:global(.lfsn49ywy) {
  stop-color: var(--svg-color--96909c, #96909C);
}

:global(.llmh6e_ej) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0.08;
}

:global(.lnj_5hbwv) {
  d: path("M2.047 5.847a3.8 3.8 0 0 1 3.8-3.8h20.306a3.8 3.8 0 0 1 3.8 3.8v20.306a3.8 3.8 0 0 1-3.8 3.8H5.847a3.8 3.8 0 0 1-3.8-3.8z");
}

:global(.lxyk3_bkx) {
  stop-color: var(--svg-color--ca4367, #CA4367);
  stop-opacity: 0.055;
}

:global(.m1796jbsw) {
  stop-color: var(--svg-color--f95a99, #F95A99);
  stop-opacity: 0.134;
}

:global(.m8ifh_wrs) {
  stop-color: var(--svg-color--d73d6f, #D73D6F);
  stop-opacity: 0.265;
}

:global(.m8ui5fbqx) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0.08;
}

:global(.mvouecbxe) {
  stop-color: var(--svg-color--ca4367, #CA4367);
}

:global(.n-wyv9crg) {
  stop-color: var(--svg-color--c23274, #C23274);
  stop-opacity: 0.134;
}

:global(.n0g19vblo) {
  stop-color: var(--svg-color--d3296e, #D3296E);
  stop-opacity: 0.055;
}

:global(.n0j5jidxu) {
  stop-color: var(--svg-color--d74568, #D74568);
  stop-opacity: 0;
}

:global(.n1y3n3bir) {
  stop-color: var(--svg-color--c74c64, #C74C64);
  stop-opacity: 0.055;
}

:global(.n2kyu5b6a) {
  stop-color: var(--svg-color--c2bec6, #C2BEC6);
  stop-opacity: 0;
}

:global(.n9zk5l6un) {
  stop-color: var(--svg-color--f95a62, #F95A62);
  stop-opacity: 0.58;
}

:global(.nfwn94blh) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
  stop-opacity: 0;
}

:global(.nfy4fkukk) {
  stop-color: var(--svg-color--ded3e7, #DED3E7);
  stop-opacity: 0;
}

:global(.nkggduuyp) {
  stop-color: var(--svg-color--f84e59, #F84E59);
  stop-opacity: 0.265;
}

:global(.nklmu6d-u) {
  stop-color: var(--svg-color--9e83b7, #9E83B7);
  stop-opacity: 0;
}

:global(.ny3yfgb0o) {
  stop-color: var(--svg-color--baacc6, #BAACC6);
}

:global(.o0ofug0up) {
  stop-color: var(--svg-color--ff63a1, #FF63A1);
}

:global(.o3pwfgfcy) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0.89;
}

:global(.o9htfcbhq) {
  stop-color: var(--svg-color--f2535b, #F2535B);
}

:global(.od5pu1k7t) {
  stop-color: var(--svg-color--c74c64, #C74C64);
}

:global(.ol0pg7b9v) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0.08;
}

:global(.omwnd69er) {
  stop-color: var(--svg-color--f95a99, #F95A99);
}

:global(.oqe73mbwe) {
  stop-color: var(--svg-color--c92064, #C92064);
  stop-opacity: 0.055;
}

:global(.pe6lqzb_l) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0;
}

:global(.qam2_0bmm) {
  stop-color: var(--svg-color--c23274, #C23274);
}

:global(.qm7qvmg_g) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
  stop-opacity: 0.319;
}

:global(.qzh-i3b7c) {
  stop-color: var(--svg-color--f95a62, #F95A62);
  stop-opacity: 0.352;
}

:global(.r2hxidb8z) {
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.rsujjy9lq) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0.215;
}

:global(.s_38r0bsq) {
  stop-color: var(--svg-color--c23240, #C23240);
  stop-opacity: 0.265;
}

:global(.s_fiwzb-w) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0.215;
}

:global(.s6ddwc0ky) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0.8;
}

:global(.s88dor6kd) {
  stop-color: var(--svg-color--f84e59, #F84E59);
}

:global(.sa_nz4b8n) {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.sm5_ixtig) {
  stop-color: var(--svg-color--eb3e7a, #EB3E7A);
  stop-opacity: 0.462;
}

:global(.smassabyb) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0.89;
}

:global(.suqznmn8o) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0.8;
}

:global(.sv2zlw2dn) {
  stop-color: var(--svg-color--e53375, #E53375);
}

:global(.tx-ejek8w) {
  stop-color: var(--svg-color--d5c9e3, #D5C9E3);
}

:global(.tz8zv0bkk) {
  stop-color: var(--svg-color--6b5f94, #6B5F94);
}

:global(.u_gy5y8lq) {
  stop-color: var(--svg-color--f7528e, #F7528E);
  stop-opacity: 0.462;
}

:global(.u0v84ib2i) {
  stop-color: var(--svg-color--d5c9e3, #D5C9E3);
  stop-opacity: 0;
}

:global(.uflad7djn) {
  stop-color: var(--svg-color--e53375, #E53375);
  stop-opacity: 0;
}

:global(.uftqaobui) {
  stop-color: var(--svg-color--988fb6, #988FB6);
  stop-opacity: 0.032;
}

:global(.uubx54jqn) {
  stop-color: var(--svg-color--fd5699, #FD5699);
  stop-opacity: 0.352;
}

:global(.uyh48sl0l) {
  stop-color: var(--svg-color--d8d1e0, #D8D1E0);
}

:global(.v-u69wa8p) {
  stop-color: var(--svg-color--c23274, #C23274);
  stop-opacity: 0.265;
}

:global(.vdus3ubud) {
  stop-color: var(--svg-color--e2dce5, #E2DCE5);
  stop-opacity: 0;
}

:global(.vhateebqh) {
  stop-color: var(--svg-color--d3296e, #D3296E);
}

:global(.viwln7b-c) {
  stop-color: var(--svg-color--fb5593, #FB5593);
  stop-opacity: 0.215;
}

:global(.vr3mtedyp) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0;
}

:global(.vsb_wlbyi) {
  stop-color: var(--svg-color--d6d1da, #D6D1DA);
}

:global(.vw2hslbkg) {
  stop-color: var(--svg-color--c74c64, #C74C64);
  stop-opacity: 0;
}

:global(.wfn3ysb9g) {
  stop-color: var(--svg-color--f4567d, #F4567D);
  stop-opacity: 0.89;
}

:global(.x06lcpb1c) {
  fill-rule: evenodd;
  d: path("M11.523 2.047h-1v8.39H2.047v1h8.476v8.97H2.047v1h8.476v8.546h1v-8.547h9v8.547h1v-8.547h8.43v-1h-8.43v-8.968h8.43v-1h-8.43V2.047h-1v8.39h-9zm9 9.39v8.97h-9v-8.97z");
}

:global(.x4aqjrs3p) {
  stop-color: var(--svg-color--f2edf5, #F2EDF5);
}

:global(.ya34kow3c) {
  stop-color: var(--svg-color--fd5699, #FD5699);
  stop-opacity: 0;
}

:global(.yb2s_2bki) {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
  stop-opacity: 0;
}

:global(.yhew10btb) {
  stop-color: var(--svg-color--d73d6f, #D73D6F);
  stop-opacity: 0;
}

:global(.ylppfgxvv) {
  stop-color: var(--svg-color--fd5699, #FD5699);
  stop-opacity: 0.8;
}

:global(.yul7fcj-a) {
  stop-color: var(--svg-color--c23240, #C23240);
  stop-opacity: 0.054;
}

:global(.z-_9w3ido) {
  stop-color: var(--svg-color--e0dfe2, #E0DFE2);
}

:global(.z2r_7ybwh) {
  stop-color: var(--svg-color--ca4367, #CA4367);
  stop-opacity: 0.265;
}

:global(.z5hhzpbhj) {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.z7-5qzbzd) {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M29.788 27.265a3.8 3.8 0 0 0 .165-1.112v-1.552l-7.083-7.083a2.5 2.5 0 0 0-3.497-.038l-1.927 1.845a.5.5 0 0 1-.699-.007L2.197 4.783a3.8 3.8 0 0 0-.15 1.064v1.612l13.286 13.274a2.5 2.5 0 0 0 3.496.037l1.927-1.845a.5.5 0 0 1 .7.007z");
}

:global(.zg2cv7mfm) {
  stop-color: var(--svg-color--ca4367, #CA4367);
  stop-opacity: 0;
}

:global(.ziha4-b7t) {
  stop-color: var(--svg-color--c92064, #C92064);
}

:global(.zj8kg6brj) {
  stop-color: var(--svg-color--a88ac4, #A88AC4);
}

:global(.znliez7ch) {
  stop-color: var(--svg-color--c23240, #C23240);
  stop-opacity: 0.134;
}

:global(.zopk7hfod) {
  stop-color: var(--svg-color--baacc6, #BAACC6);
  stop-opacity: 0;
}

:global(.zqqjoby9b) {
  stop-color: var(--svg-color--d7cde1, #D7CDE1);
}

</style>

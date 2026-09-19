<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="h6iglrbhh"/><path fill="url(#iRIpCwd)" class="j2ys4e8fx"/><path fill="url(#iz0fBoR)" class="j2ys4e8fx"/><path fill="url(#ilIRkje)" class="j2ys4e8fx"/><path fill="url(#iPsMH3c)" class="j2ys4e8fx"/><path fill="url(#iQkEWhd)" class="j2ys4e8fx"/><path fill="url(#i6yvOse)" class="j2ys4e8fx"/><path fill="url(#iIHnLwc)" class="j2ys4e8fx"/><path fill="url(#ipg1GPB)" class="j2ys4e8fx"/><path fill="url(#ifJc47d)" class="j2ys4e8fx"/><path fill="url(#ibGaQce)" class="j2ys4e8fx"/><path fill="url(#iNAl96d)" class="j2ys4e8fx"/><path fill="url(#iHtJxId)" class="j2ys4e8fx"/><path fill="url(#ipyDf8b)" class="j2ys4e8fx"/><path fill="url(#i1bNdsP)" class="j2ys4e8fx"/><path fill="url(#iSIz90d)" class="jck8ajbvs"/><path fill="url(#iUW4pRd)" class="a3kcoxb4u"/><path fill="url(#iz7VJgd)" class="s5ug07een"/><path fill="url(#iIYrhPe)" class="s5ug07een"/><path fill="url(#ieu3uMe)" class="s5ug07een"/><path fill="url(#iEIF59u)" class="s5ug07een"/><path fill="url(#ieAgLPc)" class="s5ug07een"/><path fill="url(#ioNDMbe)" class="emn-7tbrz"/><path fill="url(#irZuHmd)" class="emn-7tbrz"/><path fill="url(#iNs7vEd)" class="emn-7tbrz"/><path fill="url(#iCqm7He)" class="emn-7tbrz"/><path fill="url(#ibnIore)" class="emn-7tbrz"/><path fill="url(#iZ8xnCe)" class="fp776o_xn"/><path fill="url(#iVKvXkc)" class="fp776o_xn"/><path fill="url(#i9RnyHd)" class="fp776o_xn"/><path fill="url(#iKkVoNc)" class="fp776o_xn"/><path fill="url(#insZlde)" class="fp776o_xn"/><path fill="url(#iwHno7P)" class="fp776o_xn"/><path fill="url(#i4s42cd)" class="feitbr40s"/><path fill="url(#iF6L3CM)" class="feitbr40s"/><path fill="url(#iElRmwb)" class="feitbr40s"/><path class="s-oid7d0i"/><path fill="url(#iry7PUb)" class="tw01oq_hc"/><path fill="url(#ihG6kxe)" class="tw01oq_hc"/><path fill="url(#iRav81J)" class="tw01oq_hc"/><path fill="url(#ijLvUwb)" class="tw01oq_hc"/><path fill="url(#igU20Le)" class="tw01oq_hc"/><path fill="url(#ikP1FVc)" class="tw01oq_hc"/><path fill="url(#iU8Gz6b)" class="tw01oq_hc"/><path fill="url(#iyeBlJc)" class="tw01oq_hc"/><path fill="url(#ia7Hvud)" class="tw01oq_hc"/><path fill="url(#iUYNktd)" class="tw01oq_hc"/><path fill="url(#im4OCxc)" class="k21d8_bja"/><path fill="url(#ivbKK3b)" class="k21d8_bja"/><path fill="url(#iGnk8CW)" class="k21d8_bja"/><path fill="url(#iWeXDDd)" class="k21d8_bja"/><path fill="url(#i26aGXb)" class="k21d8_bja"/><path fill="url(#itRXFbk)" class="k21d8_bja"/><path fill="url(#i4p73Nb)" class="k21d8_bja"/><path fill="url(#iBYsyle)" class="k21d8_bja"/><path fill="url(#iKX1tAb)" class="k21d8_bja"/><path fill="url(#i1v9Ked)" class="k21d8_bja"/></g><defs><radialGradient id="ilIRkje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.50001 10.00002 -24.1071 -3.61608 14.193 21)" gradientUnits="userSpaceOnUse"><stop offset=".294" class="eebf5ub9j"/><stop offset=".874" class="k90wp6bmc"/></radialGradient><radialGradient id="i6yvOse" cx="0" cy="0" r="1" gradientTransform="matrix(-.68767 6.50126 -6.0031 -.63498 17.372 20.942)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="i6o-qu9fo"/><stop offset="1" class="r5htkxbvz"/></radialGradient><radialGradient id="iIHnLwc" cx="0" cy="0" r="1" gradientTransform="matrix(.53853 7.97018 -6.15248 .41571 16.793 21.648)" gradientUnits="userSpaceOnUse"><stop offset=".462" class="pf1xml9sl"/><stop offset="1" class="rd54rdzck"/></radialGradient><radialGradient id="ipg1GPB" cx="0" cy="0" r="1" gradientTransform="matrix(16.01925 10.36522 -13.13305 20.29688 1.187 16.766)" gradientUnits="userSpaceOnUse"><stop offset=".974" class="v10_5zwzh"/><stop offset="1" class="jn_5q-btc"/></radialGradient><radialGradient id="ibGaQce" cx="0" cy="0" r="1" gradientTransform="matrix(-7.822 5.35543 -6.78547 -9.91068 16.526 26.128)" gradientUnits="userSpaceOnUse"><stop class="yk1d-rbcz"/><stop offset="1" class="vy67icc3g"/></radialGradient><radialGradient id="iNAl96d" cx="0" cy="0" r="1" gradientTransform="rotate(18.358 -64.51 3.674)scale(20.8924 11.2164)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="i-lj0-gmv"/><stop offset="1" class="vvyrbnhyh"/></radialGradient><radialGradient id="ipyDf8b" cx="0" cy="0" r="1" gradientTransform="matrix(.37564 6.01026 -5.0257 .3141 16.39 23.032)" gradientUnits="userSpaceOnUse"><stop offset=".02" class="gkxiyeb3x"/><stop offset=".645" class="gkxiyeb3x"/><stop offset=".705" class="s4qko67rc"/><stop offset=".947" class="gkxiyeb3x"/></radialGradient><radialGradient id="i1bNdsP" cx="0" cy="0" r="1" gradientTransform="rotate(90.939 -.685 17.182)scale(8.59395 7.27784)" gradientUnits="userSpaceOnUse"><stop offset=".513" class="tqnkvib7j"/><stop offset="1" class="bdynesb7r"/></radialGradient><radialGradient id="iIYrhPe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4421 -8.96427 5.94373 .95618 22.363 16.384)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="ex9n-fxyw"/><stop offset="1" class="iced9wbnh"/></radialGradient><radialGradient id="ieu3uMe" cx="0" cy="0" r="1" gradientTransform="matrix(.24459 3.88283 -.58052 .03657 22.623 11.08)" gradientUnits="userSpaceOnUse"><stop class="xmaahdcof"/><stop offset="1" class="g0iq_abpf"/></radialGradient><radialGradient id="ieAgLPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.595 1.26543 -1.54308 -.72556 24.4 8.241)" gradientUnits="userSpaceOnUse"><stop class="q3dbbul_o"/><stop offset="1" class="bcvvplhru"/></radialGradient><radialGradient id="irZuHmd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.05948 -9.0811 5.42069 -1.82626 23.38 13.945)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="jr7qwdkiz"/><stop offset="1" class="oqlhmxbxb"/></radialGradient><radialGradient id="iNs7vEd" cx="0" cy="0" r="1" gradientTransform="matrix(.2503 4.43595 -.59456 .03355 20.225 9.204)" gradientUnits="userSpaceOnUse"><stop class="xmaahdcof"/><stop offset="1" class="g0iq_abpf"/></radialGradient><radialGradient id="ibnIore" cx="0" cy="0" r="1" gradientTransform="rotate(112.841 9.043 10.298)scale(1.56871 1.77711)" gradientUnits="userSpaceOnUse"><stop class="q3dbbul_o"/><stop offset="1" class="bcvvplhru"/></radialGradient><radialGradient id="iVKvXkc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.96832 -10.83226 8.09845 -3.71443 21.462 13.86)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="jr7qwdkiz"/><stop offset="1" class="oqlhmxbxb"/></radialGradient><radialGradient id="i9RnyHd" cx="0" cy="0" r="1" gradientTransform="rotate(79.432 4.426 14.377)scale(6.61961 1.20465)" gradientUnits="userSpaceOnUse"><stop class="xmaahdcof"/><stop offset="1" class="g0iq_abpf"/></radialGradient><radialGradient id="iKkVoNc" cx="0" cy="0" r="1" gradientTransform="matrix(.82556 5.24471 -.52213 .08219 17.844 8.749)" gradientUnits="userSpaceOnUse"><stop class="xmaahdcof"/><stop offset=".746" class="g0iq_abpf"/></radialGradient><radialGradient id="iwHno7P" cx="0" cy="0" r="1" gradientTransform="rotate(119.832 8.39 7.757)scale(1.98789 2.71654)" gradientUnits="userSpaceOnUse"><stop class="q3dbbul_o"/><stop offset="1" class="bcvvplhru"/></radialGradient><radialGradient id="iF6L3CM" cx="0" cy="0" r="1" gradientTransform="rotate(54.573 2.424 19.158)scale(2.55309 3.33848)" gradientUnits="userSpaceOnUse"><stop class="mbddftdke"/><stop offset="1" class="sn4_rsbwk"/></radialGradient><radialGradient id="ihG6kxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.55105 7.96632 -4.84722 -.3353 11.756 18.745)" gradientUnits="userSpaceOnUse"><stop offset=".644" class="vgnpela3x"/><stop offset="1" class="hxcuw3bgx"/></radialGradient><radialGradient id="iRav81J" cx="0" cy="0" r="1" gradientTransform="matrix(-.43559 6.7733 -4.1213 -.26504 11.756 18.745)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="pe6kzb4cs"/><stop offset=".278" class="emcp6uprx"/><stop offset="1" class="ghoubbbbl"/><stop offset="1" class="o2h_vobur"/></radialGradient><radialGradient id="ijLvUwb" cx="0" cy="0" r="1" gradientTransform="rotate(51.318 -5.992 23.676)scale(4.16933 2.06214)" gradientUnits="userSpaceOnUse"><stop class="aj9ngsbgl"/><stop offset=".943" class="gsplgq0ij"/></radialGradient><radialGradient id="igU20Le" cx="0" cy="0" r="1" gradientTransform="rotate(54.904 -4.576 20.914)scale(2.19606 2.27843)" gradientUnits="userSpaceOnUse"><stop class="tmustgbye"/><stop offset="1" class="otqui3b-n"/></radialGradient><radialGradient id="iU8Gz6b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.33231 -3.55487 2.163 -3.24452 15.9 23.662)" gradientUnits="userSpaceOnUse"><stop class="h5q30obfn"/><stop offset="1" class="x63q6kbba"/><stop offset="1" class="qe9sp2uck"/></radialGradient><radialGradient id="iyeBlJc" cx="0" cy="0" r="1" gradientTransform="matrix(.32838 4.59737 -1.91946 .1371 13.252 21.365)" gradientUnits="userSpaceOnUse"><stop class="q9joypnaf"/><stop offset="1" class="lcsu3ebfj"/></radialGradient><radialGradient id="ia7Hvud" cx="0" cy="0" r="1" gradientTransform="matrix(.25262 8.3351 -7.18888 .21788 19.943 17.18)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="jroab800w"/><stop offset=".48" class="j5-kcqb9i"/></radialGradient><radialGradient id="iUYNktd" cx="0" cy="0" r="1" gradientTransform="rotate(56.945 -5.395 22.268)scale(4.89086 2.3193)" gradientUnits="userSpaceOnUse"><stop class="sie44bdiq"/><stop offset="1" class="moqbay-5a"/></radialGradient><radialGradient id="im4OCxc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4826 1.59919 -1.46857 2.27982 13.593 23.916)" gradientUnits="userSpaceOnUse"><stop class="ue__facgg"/><stop offset=".995" class="ursx7acdv"/></radialGradient><radialGradient id="ivbKK3b" cx="0" cy="0" r="1" gradientTransform="rotate(79.606 -6.865 18.523)scale(2.94131 .99204)" gradientUnits="userSpaceOnUse"><stop class="q3jsftb0t"/><stop offset="1" class="vks1df7vt"/></radialGradient><radialGradient id="iGnk8CW" cx="0" cy="0" r="1" gradientTransform="rotate(96.195 1.298 17.655)scale(4.53816 2.72633)" gradientUnits="userSpaceOnUse"><stop class="fyjzfdcis"/><stop offset="1" class="k3vk2eo4p"/></radialGradient><radialGradient id="iWeXDDd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.39678 13.27575 -12.1914 -6.79262 25.897 12.693)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="mx737wb9p"/><stop offset=".784" class="kgqg76cyv"/><stop offset="1" class="q92t9ub7h"/></radialGradient><radialGradient id="i26aGXb" cx="0" cy="0" r="1" gradientTransform="rotate(113.453 4.39 16.202)scale(6.88395 4.13558)" gradientUnits="userSpaceOnUse"><stop class="mjldw5tvh"/><stop offset="1" class="scsrdpwzj"/></radialGradient><radialGradient id="itRXFbk" cx="0" cy="0" r="1" gradientTransform="rotate(94.279 1.775 16.791)scale(2.03257 .86339)" gradientUnits="userSpaceOnUse"><stop class="ckve3rb-m"/><stop offset="1" class="k5rak5p1i"/></radialGradient><radialGradient id="i4p73Nb" cx="0" cy="0" r="1" gradientTransform="rotate(57.036 -4.388 22.41)scale(3.95275 .14077)" gradientUnits="userSpaceOnUse"><stop class="be2kofmqw"/><stop offset=".593" class="g_ghw7l4r"/></radialGradient><radialGradient id="iBYsyle" cx="0" cy="0" r="1" gradientTransform="rotate(102.025 -1.78 15.965)scale(4.07208 .82555)" gradientUnits="userSpaceOnUse"><stop class="jki1i3y-w"/><stop offset=".794" class="llr_hxb2h"/></radialGradient><radialGradient id="iKX1tAb" cx="0" cy="0" r="1" gradientTransform="rotate(117.867 2.58 15.912)scale(3.95251 3.62968)" gradientUnits="userSpaceOnUse"><stop class="rjmzy1b9j"/><stop offset="1" class="t8f5edc0z"/></radialGradient><radialGradient id="i1v9Ked" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36854 5.49678 -5.0478 -2.17508 20.87 19.299)" gradientUnits="userSpaceOnUse"><stop class="dxq4xkb0h"/><stop offset="1" class="f2w21v6rd"/></radialGradient><linearGradient id="iRIpCwd" x1="8.193" x2="8.704" y1="27" y2="31.063" gradientUnits="userSpaceOnUse"><stop offset=".456" class="wz0ektb2t"/><stop offset=".974" class="ink3gpbzz"/><stop offset="1" class="odhggkl1x"/></linearGradient><linearGradient id="iz0fBoR" x1="15.192" x2="12.067" y1="30.047" y2="22.991" gradientUnits="userSpaceOnUse"><stop class="ajic0q7cm"/><stop offset="1" class="m7gdckjal"/></linearGradient><linearGradient id="iPsMH3c" x1="-.857" x2="6.817" y1="27.45" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="v6d9zubux"/><stop offset="1" class="bh-87dbgb"/></linearGradient><linearGradient id="iQkEWhd" x1="6.443" x2="8.255" y1="18.063" y2="30.25" gradientUnits="userSpaceOnUse"><stop offset=".052" class="gmmht-bmp"/><stop offset=".313" class="pe70qdb4r"/><stop offset=".716" class="gmmht-bmp"/></linearGradient><linearGradient id="ifJc47d" x1="8.704" x2="8.704" y1="17.278" y2="31.483" gradientUnits="userSpaceOnUse"><stop offset=".25" class="glhjr8b8a"/><stop offset=".658" class="dfx-3gbqu"/><stop offset="1" class="v3mqk9bny"/></linearGradient><linearGradient id="iHtJxId" x1="7.575" x2="8.418" y1="26.209" y2="30.964" gradientUnits="userSpaceOnUse"><stop offset=".67" class="s-b47gbty"/><stop offset=".804" class="j-f1eub7w"/></linearGradient><linearGradient id="iSIz90d" x1="13.565" x2="15.676" y1="21.022" y2="26.633" gradientUnits="userSpaceOnUse"><stop class="b98-tgbhp"/><stop offset=".525" class="qn2ni9zxl"/><stop offset=".844" class="w8l_z4boy"/><stop offset=".932" class="ph9_gqbzs"/></linearGradient><linearGradient id="iUW4pRd" x1="21.091" x2="18.928" y1="13.283" y2="25.969" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ytmhq0bfh"/><stop offset=".381" class="n1une6uzg"/><stop offset=".598" class="g_7zxzbnj"/><stop offset="1" class="g2d3tbc9h"/></linearGradient><linearGradient id="iz7VJgd" x1="25.248" x2="20.906" y1="11.857" y2="11.887" gradientUnits="userSpaceOnUse"><stop class="asfjhybkb"/><stop offset=".185" class="ealbv0b4u"/><stop offset=".333" class="rwgtpmbwo"/><stop offset=".526" class="see7sxafx"/><stop offset=".616" class="ixtctsbmd"/><stop offset=".722" class="tjs3c7bbx"/></linearGradient><linearGradient id="iEIF59u" x1="24.567" x2="23.364" y1="12.797" y2="15.125" gradientUnits="userSpaceOnUse"><stop offset=".219" class="xm0oy-blt"/><stop offset=".572" class="f4rux0yrp"/></linearGradient><linearGradient id="ioNDMbe" x1="22.911" x2="18.467" y1="10.091" y2="10.119" gradientUnits="userSpaceOnUse"><stop class="asfjhybkb"/><stop offset=".185" class="ealbv0b4u"/><stop offset=".333" class="rwgtpmbwo"/><stop offset=".526" class="see7sxafx"/><stop offset=".616" class="ixtctsbmd"/><stop offset=".722" class="tjs3c7bbx"/></linearGradient><linearGradient id="iCqm7He" x1="22.214" x2="20.755" y1="11.166" y2="13.695" gradientUnits="userSpaceOnUse"><stop offset=".219" class="xm0oy-blt"/><stop offset=".572" class="f4rux0yrp"/></linearGradient><linearGradient id="iZ8xnCe" x1="20.699" x2="13.483" y1="9.265" y2="9.326" gradientUnits="userSpaceOnUse"><stop class="asfjhybkb"/><stop offset=".185" class="ealbv0b4u"/><stop offset=".333" class="rwgtpmbwo"/><stop offset=".526" class="see7sxafx"/><stop offset=".616" class="ixtctsbmd"/><stop offset=".722" class="tjs3c7bbx"/></linearGradient><linearGradient id="insZlde" x1="19.567" x2="18.123" y1="10.546" y2="13.954" gradientUnits="userSpaceOnUse"><stop offset=".219" class="xm0oy-blt"/><stop offset=".572" class="f4rux0yrp"/></linearGradient><linearGradient id="i4s42cd" x1="18.54" x2="12.634" y1="11.471" y2="12.27" gradientUnits="userSpaceOnUse"><stop class="jxu1d-bpr"/><stop offset=".157" class="gb91t-3wl"/><stop offset=".354" class="daz4vzbns"/><stop offset=".454" class="hfvyq_rrq"/><stop offset=".637" class="udv_ilqet"/><stop offset=".774" class="yxz9x5ezq"/></linearGradient><linearGradient id="iElRmwb" x1="14.525" x2="18.88" y1="4.354" y2="13.633" gradientUnits="userSpaceOnUse"><stop offset=".835" class="hc1xmbcsr"/><stop offset="1" class="y8_6svbfy"/></linearGradient><linearGradient id="iry7PUb" x1="12.887" x2="15.167" y1="11.278" y2="20.688" gradientUnits="userSpaceOnUse"><stop class="torrslb_c"/><stop offset="1" class="d018i1g2k"/></linearGradient><linearGradient id="ikP1FVc" x1="19.167" x2="17.285" y1="18.976" y2="19.207" gradientUnits="userSpaceOnUse"><stop class="mtq818brl"/><stop offset="1" class="y1zei88ik"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:rightwards-pushing-hand-medium-light" {...props}></Icon>
<style>
:global(.a3kcoxb4u) {
  d: path("M23.782 21.687c-1.05 2.271-3.92 3.744-5.222 4.196c-.56.18-2.161.195-4.087-1.184c-2.408-1.723-1.135-4.65-1.068-4.96s.31-.93.343-1.113c.034-.184-.1-.954-.284-1.44c-.148-.388-.63-1.311-.854-1.724l2.83-3.332l9.772-.255c.026 1.097.062 3.58 0 4.74l-.001.011c-.078 1.442-.12 2.229-1.43 5.06");
}

:global(.aj9ngsbgl) {
  stop-color: var(--svg-color--f9c9a5, #F9C9A5);
}

:global(.ajic0q7cm) {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
}

:global(.asfjhybkb) {
  stop-color: var(--svg-color--edc19d, #EDC19D);
}

:global(.b98-tgbhp) {
  stop-color: var(--svg-color--9a695f, #9A695F);
}

:global(.bcvvplhru) {
  stop-color: var(--svg-color--fccda7, #FCCDA7);
  stop-opacity: 0;
}

:global(.bdynesb7r) {
  stop-color: var(--svg-color--572685, #572685);
  stop-opacity: 0;
}

:global(.be2kofmqw) {
  stop-color: var(--svg-color--d49873, #D49873);
}

:global(.bh-87dbgb) {
  stop-color: var(--svg-color--465eff, #465EFF);
  stop-opacity: 0;
}

:global(.ckve3rb-m) {
  stop-color: var(--svg-color--ffcda8, #FFCDA8);
}

:global(.d018i1g2k) {
  stop-color: var(--svg-color--dbac8b, #DBAC8B);
  stop-opacity: 0;
}

:global(.daz4vzbns) {
  stop-color: var(--svg-color--e2ae91, #E2AE91);
}

:global(.dfx-3gbqu) {
  stop-color: var(--svg-color--5736f5, #5736F5);
}

:global(.dxq4xkb0h) {
  stop-color: var(--svg-color--f6c1a0, #F6C1A0);
}

:global(.ealbv0b4u) {
  stop-color: var(--svg-color--f9c7a4, #F9C7A4);
}

:global(.eebf5ub9j) {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
}

:global(.emcp6uprx) {
  stop-color: var(--svg-color--be8080, #BE8080);
}

:global(.emn-7tbrz) {
  d: path("M22.61 10.705c.037 1.253.216 2.174.301 2.477c-.966-.182-2.697-.41-2.587-2.714a96 96 0 0 0-.11-2.451c-.036-.629-.136-2.46-.255-3.389c.256-.036.693-.128 1.476.383c.784.51.83 1.339.92 1.977c.091.637.21 2.15.255 3.716");
}

:global(.ex9n-fxyw) {
  stop-color: var(--svg-color--d8a781, #D8A781);
  stop-opacity: 0;
}

:global(.f2w21v6rd) {
  stop-color: var(--svg-color--f6c1a0, #F6C1A0);
  stop-opacity: 0;
}

:global(.f4rux0yrp) {
  stop-color: var(--svg-color--fecba4, #FECBA4);
}

:global(.feitbr40s) {
  d: path("M18.288 10.228c.216 1.956.585 2.715.743 2.85c-.198 1.232-.184 4.19-.743 4.61c-.966.726-2.704-1.725-3.446-2.076l-.417-3.03c-.203-1.63-.626-5.025-.698-5.575c-.09-.686.135-2.398 1.824-2.455s2.174 1.374 2.264 1.949l.003.02c.09.57.203 1.291.47 3.707");
}

:global(.fp776o_xn) {
  d: path("M20.322 10.028c.063 1.683.267 1.688.377 1.974c-1.07 1.51-3.642.886-4.793.385v-7.76c.107-.716.707-2.1 2.245-1.895c1.923.255 1.88 2.214 1.958 3.315s.165 2.864.212 3.98");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.fyjzfdcis) {
  stop-color: var(--svg-color--fac5a2, #FAC5A2);
}

:global(.g_7zxzbnj) {
  stop-color: var(--svg-color--ebb29a, #EBB29A);
}

:global(.g_ghw7l4r) {
  stop-color: var(--svg-color--d49873, #D49873);
  stop-opacity: 0;
}

:global(.g0iq_abpf) {
  stop-color: var(--svg-color--c47e5e, #C47E5E);
  stop-opacity: 0;
}

:global(.g2d3tbc9h) {
  stop-color: var(--svg-color--bc7a8b, #BC7A8B);
}

:global(.gb91t-3wl) {
  stop-color: var(--svg-color--f7c5a4, #F7C5A4);
}

:global(.ghoubbbbl) {
  stop-color: var(--svg-color--915b6d, #915B6D);
  stop-opacity: 0;
}

:global(.gkxiyeb3x) {
  stop-color: var(--svg-color--7232f9, #7232F9);
  stop-opacity: 0;
}

:global(.glhjr8b8a) {
  stop-color: var(--svg-color--603d8b, #603D8B);
}

:global(.gmmht-bmp) {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0;
}

:global(.gsplgq0ij) {
  stop-color: var(--svg-color--f9c9a5, #F9C9A5);
  stop-opacity: 0;
}

:global(.h5q30obfn) {
  stop-color: var(--svg-color--ca8b90, #CA8B90);
}

:global(.h6iglrbhh) {
  fill: var(--svg-color--8248dd, #8248DD);
  d: path("m17.703 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L-.295 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

:global(.hc1xmbcsr) {
  stop-color: var(--svg-color--ffcea9, #FFCEA9);
  stop-opacity: 0;
}

:global(.hfvyq_rrq) {
  stop-color: var(--svg-color--d7a285, #D7A285);
}

:global(.hxcuw3bgx) {
  stop-color: var(--svg-color--d59991, #D59991);
  stop-opacity: 0;
}

:global(.i-lj0-gmv) {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
  stop-opacity: 0;
}

:global(.i6o-qu9fo) {
  stop-color: var(--svg-color--852dbd, #852DBD);
}

:global(.iced9wbnh) {
  stop-color: var(--svg-color--d8a781, #D8A781);
}

:global(.ink3gpbzz) {
  stop-color: var(--svg-color--9d68ff, #9D68FF);
}

:global(.ixtctsbmd) {
  stop-color: var(--svg-color--c5805f, #C5805F);
}

:global(.j-f1eub7w) {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
}

:global(.j2ys4e8fx) {
  d: path("m17.703 26.047l-3.027-8.769c-.059.216-.94.29-1.373.3L-.295 19.93v11.553l14.752-2.527c2.322-.306 3.126-2.074 3.246-2.91");
}

:global(.j5-kcqb9i) {
  stop-color: var(--svg-color--fbc6a2, #FBC6A2);
  stop-opacity: 0;
}

:global(.jck8ajbvs) {
  d: path("M17.242 26.225c.865-.173 1.417-.37 1.584-.447c-2.339-3.984-6.979-11.862-6.829-11.512c.188.437 1.016 2 1.383 2.718c.367.72.36 1.602.36 1.758s-.29.68-.36 1.008c-.07.078-.633.625-.797 1.828c-.131.963-.099 1.622-.066 1.832c.094 1.241.6 1.906 1.021 2.384c.734.834 1.871.87 2.136.828c.138-.022.486-.182 1.568-.397");
}

:global(.jki1i3y-w) {
  stop-color: var(--svg-color--c08c79, #C08C79);
}

:global(.jn_5q-btc) {
  stop-color: var(--svg-color--806dd1, #806DD1);
}

:global(.jr7qwdkiz) {
  stop-color: var(--svg-color--d9a984, #D9A984);
  stop-opacity: 0;
}

:global(.jroab800w) {
  stop-color: var(--svg-color--fbc6a2, #FBC6A2);
}

:global(.jxu1d-bpr) {
  stop-color: var(--svg-color--f3c19b, #F3C19B);
}

:global(.k21d8_bja) {
  d: path("m15.575 12.126l9.637-.25c.026 1.096.062 3.58 0 4.739l-.001.011c-.078 1.442-.12 2.229-1.43 5.06c-1.049 2.273-3.918 3.745-5.221 4.198c-.56.18-2.161.194-4.087-1.185c-1.46-1.044-1.567-2.532-1.41-3.61q.009-.13.024-.268c.034-.329.245-.941.423-1.457c.103-.298.194-.564.234-.724l.005-.022c.029-.197-.104-.953-.285-1.432c-.148-.388-.63-1.31-.854-1.724l.009-.01c-.17-.314-.361-.673-.574-1.099c-.764-1.528.047-3.165 1.684-3.071c.906.052 1.406.318 1.846.844");
}

:global(.k3vk2eo4p) {
  stop-color: var(--svg-color--fac5a2, #FAC5A2);
  stop-opacity: 0;
}

:global(.k5rak5p1i) {
  stop-color: var(--svg-color--ffcda8, #FFCDA8);
  stop-opacity: 0;
}

:global(.k90wp6bmc) {
  stop-color: var(--svg-color--8e4ae5, #8E4AE5);
  stop-opacity: 0;
}

:global(.kgqg76cyv) {
  stop-color: var(--svg-color--d79b95, #D79B95);
  stop-opacity: 0;
}

:global(.lcsu3ebfj) {
  stop-color: var(--svg-color--c58e7d, #C58E7D);
  stop-opacity: 0;
}

:global(.llr_hxb2h) {
  stop-color: var(--svg-color--c08c79, #C08C79);
  stop-opacity: 0;
}

:global(.m7gdckjal) {
  stop-color: var(--svg-color--5d3ad5, #5D3AD5);
  stop-opacity: 0;
}

:global(.mbddftdke) {
  stop-color: var(--svg-color--fbcda9, #FBCDA9);
}

:global(.mjldw5tvh) {
  stop-color: var(--svg-color--fac5a1, #FAC5A1);
}

:global(.moqbay-5a) {
  stop-color: var(--svg-color--f1bc9e, #F1BC9E);
  stop-opacity: 0;
}

:global(.mtq818brl) {
  stop-color: var(--svg-color--f8c3a1, #F8C3A1);
}

:global(.mx737wb9p) {
  stop-color: var(--svg-color--ba7984, #BA7984);
  stop-opacity: 0;
}

:global(.n1une6uzg) {
  stop-color: var(--svg-color--fac4a0, #FAC4A0);
}

:global(.o2h_vobur) {
  stop-color: var(--svg-color--be8080, #BE8080);
  stop-opacity: 0;
}

:global(.odhggkl1x) {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
  stop-opacity: 0;
}

:global(.oqlhmxbxb) {
  stop-color: var(--svg-color--d9a984, #D9A984);
}

:global(.otqui3b-n) {
  stop-color: var(--svg-color--fbcbaa, #FBCBAA);
  stop-opacity: 0;
}

:global(.pe6kzb4cs) {
  stop-color: var(--svg-color--bb8778, #BB8778);
}

:global(.pe70qdb4r) {
  stop-color: var(--svg-color--a4a7ff, #A4A7FF);
  stop-opacity: 0.62;
}

:global(.pf1xml9sl) {
  stop-color: var(--svg-color--852aab, #852AAB);
}

:global(.ph9_gqbzs) {
  stop-color: var(--svg-color--af6a88, #AF6A88);
}

:global(.q3dbbul_o) {
  stop-color: var(--svg-color--fccda7, #FCCDA7);
}

:global(.q3jsftb0t) {
  stop-color: var(--svg-color--a26f68, #A26F68);
}

:global(.q92t9ub7h) {
  stop-color: var(--svg-color--ba7984, #BA7984);
}

:global(.q9joypnaf) {
  stop-color: var(--svg-color--c58e7d, #C58E7D);
}

:global(.qe9sp2uck) {
  stop-color: var(--svg-color--ca8b90, #CA8B90);
  stop-opacity: 0;
}

:global(.qn2ni9zxl) {
  stop-color: var(--svg-color--ad7674, #AD7674);
}

:global(.r5htkxbvz) {
  stop-color: var(--svg-color--852dbd, #852DBD);
  stop-opacity: 0;
}

:global(.rd54rdzck) {
  stop-color: var(--svg-color--6f32fb, #6F32FB);
  stop-opacity: 0;
}

:global(.rjmzy1b9j) {
  stop-color: var(--svg-color--e2a898, #E2A898);
}

:global(.rwgtpmbwo) {
  stop-color: var(--svg-color--f2bd9e, #F2BD9E);
}

:global(.s-b47gbty) {
  stop-color: var(--svg-color--9d6aff, #9D6AFF);
  stop-opacity: 0;
}

:global(.s-oid7d0i) {
  fill: var(--svg-color--e1a896, #E1A896);
  d: path("M16.7 13.928c.819 1.407 1.593 2.091 1.878 2.257c.088.05 1.863 2.455-1.212 5.876c-1.668 1.469-4.849 3.505-4.279-1.24c.063-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

:global(.s4qko67rc) {
  stop-color: var(--svg-color--7232f9, #7232F9);
}

:global(.s5ug07een) {
  d: path("m25.188 11.896l.06 2.666c-1.687-.202-2.602-1.26-2.602-2.743c-.012-.255-.046-.838-.09-1.767c-.035-.742-.143-2.258-.192-2.923c.252-.083.896-.174 1.454.123c1.352.608 1.252 1.987 1.37 4.644");
}

:global(.scsrdpwzj) {
  stop-color: var(--svg-color--fac5a1, #FAC5A1);
  stop-opacity: 0;
}

:global(.see7sxafx) {
  stop-color: var(--svg-color--d6977a, #D6977A);
}

:global(.sie44bdiq) {
  stop-color: var(--svg-color--f1bc9e, #F1BC9E);
}

:global(.sn4_rsbwk) {
  stop-color: var(--svg-color--fbcda9, #FBCDA9);
  stop-opacity: 0;
}

:global(.t8f5edc0z) {
  stop-color: var(--svg-color--e2a898, #E2A898);
  stop-opacity: 0;
}

:global(.tjs3c7bbx) {
  stop-color: var(--svg-color--c8805c, #C8805C);
}

:global(.tmustgbye) {
  stop-color: var(--svg-color--fbcbaa, #FBCBAA);
}

:global(.torrslb_c) {
  stop-color: var(--svg-color--dbac8b, #DBAC8B);
}

:global(.tqnkvib7j) {
  stop-color: var(--svg-color--572685, #572685);
}

:global(.tw01oq_hc) {
  d: path("M16.7 13.928c.819 1.407 1.593 2.091 1.878 2.257c.088.05 1.863 2.455-1.212 5.876c-1.668 1.469-4.849 3.505-4.279-1.24c.063-.517.56-1.798.658-2.18c.03-.317-.146-.993-.255-1.29c-.234-.764-.681-1.413-1.445-2.94c-.764-1.529.047-3.223 1.684-3.13c1.637.094 1.95.888 2.972 2.647");
}

:global(.udv_ilqet) {
  stop-color: var(--svg-color--c08b6e, #C08B6E);
}

:global(.ue__facgg) {
  stop-color: var(--svg-color--a97370, #A97370);
}

:global(.ursx7acdv) {
  stop-color: var(--svg-color--a97370, #A97370);
  stop-opacity: 0;
}

:global(.v10_5zwzh) {
  stop-color: var(--svg-color--806dd1, #806DD1);
  stop-opacity: 0;
}

:global(.v3mqk9bny) {
  stop-color: var(--svg-color--603d8b, #603D8B);
  stop-opacity: 0;
}

:global(.v6d9zubux) {
  stop-color: var(--svg-color--465eff, #465EFF);
}

:global(.vgnpela3x) {
  stop-color: var(--svg-color--d59991, #D59991);
}

:global(.vks1df7vt) {
  stop-color: var(--svg-color--a26f68, #A26F68);
  stop-opacity: 0;
}

:global(.vvyrbnhyh) {
  stop-color: var(--svg-color--a58ff2, #A58FF2);
}

:global(.vy67icc3g) {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
  stop-opacity: 0;
}

:global(.w8l_z4boy) {
  stop-color: var(--svg-color--ae6d81, #AE6D81);
}

:global(.wycjhibbk) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

:global(.wz0ektb2t) {
  stop-color: var(--svg-color--4d51ff, #4D51FF);
}

:global(.x63q6kbba) {
  stop-color: var(--svg-color--a26783, #A26783);
  stop-opacity: 0;
}

:global(.xm0oy-blt) {
  stop-color: var(--svg-color--fecba4, #FECBA4);
  stop-opacity: 0;
}

:global(.xmaahdcof) {
  stop-color: var(--svg-color--c47e5e, #C47E5E);
}

:global(.y1zei88ik) {
  stop-color: var(--svg-color--f8c3a1, #F8C3A1);
  stop-opacity: 0;
}

:global(.y8_6svbfy) {
  stop-color: var(--svg-color--ffcea9, #FFCEA9);
}

:global(.yk1d-rbcz) {
  stop-color: var(--svg-color--5c3bd1, #5C3BD1);
}

:global(.ytmhq0bfh) {
  stop-color: var(--svg-color--ffcea8, #FFCEA8);
}

:global(.yxz9x5ezq) {
  stop-color: var(--svg-color--ce977c, #CE977C);
}

</style>

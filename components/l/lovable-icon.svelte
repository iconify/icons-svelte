<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":261};
const content = `<defs><radialGradient id="SVGL9CZzb2N" cx="7.166%" cy="52.108%" r="113.046%" fx="7.166%" fy="52.108%" gradientTransform="matrix(.1701 0 0 1 .06 0)"><stop offset="0%" class="oz8r6fb1c"/><stop offset="17%" class="lil77pbyz"/><stop offset="25%" class="xs03cac7x"/><stop offset="31%" class="ihv_n_b2c"/><stop offset="33.5%" class="nag_lxbvx"/><stop offset="36.5%" class="iznxipmlg"/><stop offset="39%" class="vbeo9sbux"/><stop offset="41.5%" class="e6723-b8l"/><stop offset="44%" class="uy4agtbrg"/><stop offset="46.5%" class="k7rh_ebdt"/><stop offset="49%" class="thorri0bf"/><stop offset="51.5%" class="fem56kbcc"/><stop offset="57.5%" class="jv7r6gbwh"/><stop offset="61.5%" class="c6y42_gyr"/><stop offset="63.5%" class="t7sxtwb5g"/><stop offset="65%" class="qsndi2b3f"/><stop offset="68%" class="bbijpbcqe"/><stop offset="70%" class="h5owgwbla"/><stop offset="72.5%" class="y1xxxxb1b"/><stop offset="74.5%" class="zesg976so"/><stop offset="77.5%" class="cj425sbmd"/><stop offset="82.5%" class="kchlv0gcs"/><stop offset="89%" class="nmhantbyb"/><stop offset="100%" class="eo-4m3-dp"/></radialGradient><radialGradient id="SVGyW8gxczB" cx="8.381%" cy="16.444%" r="131.291%" fx="8.381%" fy="16.444%" gradientTransform="matrix(.1701 0 0 1 .07 0)"><stop offset="0%" class="h573bzbkh"/><stop offset="27%" class="k72_dmiob"/><stop offset="33%" class="ky33i4bxn"/><stop offset="38%" class="g9pcewb2x"/><stop offset="42%" class="c7qxjz4xc"/><stop offset="44%" class="wdum75b7p"/><stop offset="47.5%" class="xy4iqmbal"/><stop offset="50%" class="shuqpmb1r"/><stop offset="52%" class="y0whgv90r"/><stop offset="55.5%" class="tsba924uk"/><stop offset="62.5%" class="epm5p4-sr"/><stop offset="65.5%" class="y4s2hccpv"/><stop offset="67%" class="wh_2zyb_e"/><stop offset="69.5%" class="idm0p2b6p"/><stop offset="73%" class="rwykwco9p"/><stop offset="74.5%" class="ccb3h2b-r"/><stop offset="78.5%" class="pu6l-ebjo"/><stop offset="81.5%" class="plv_hzbmr"/><stop offset="84%" class="kkh1ypb6l"/><stop offset="90.5%" class="j7n3rmbkg"/><stop offset="100%" class="urzwv28ey"/></radialGradient><radialGradient id="SVG4pwrbdCB" cx="10.691%" cy="4.219%" r="113.046%" fx="10.691%" fy="4.219%" gradientTransform="matrix(.1701 0 0 1 .089 0)"><stop offset="0%" class="k0qrvrche"/><stop offset="14.5%" class="h096c3bpq"/><stop offset="22.5%" class="ofh3ubddq"/><stop offset="29%" class="v7rducuos"/><stop offset="31.5%" class="oinsvpbpq"/><stop offset="34%" class="cjn27pa5f"/><stop offset="38.5%" class="bz2nbh6bo"/><stop offset="42%" class="mz_wmfqco"/><stop offset="44%" class="fdnai5bpm"/><stop offset="46%" class="sfzo59b8s"/><stop offset="50%" class="nv85m5bop"/><stop offset="59%" class="x3my7-tnb"/><stop offset="63%" class="na9h9nb7b"/><stop offset="67%" class="zv5zsmbcx"/><stop offset="71%" class="f7-ean4-g"/><stop offset="74%" class="n73wcjkkd"/><stop offset="76.5%" class="mmi_d9b0k"/><stop offset="82%" class="loi85ac1q"/><stop offset="89%" class="wa6txjb6y"/><stop offset="100%" class="tamj2ub2k"/></radialGradient><radialGradient id="SVGHRCAsbwa" cx="8.578%" cy="16.431%" r="87.141%" fx="8.578%" fy="16.431%" gradientTransform="matrix(.1701 0 0 1 .071 0)"><stop offset="0%" class="lxvp1_b8m"/><stop offset="7%" class="a50azibyu"/><stop offset="13.5%" class="nepzut_yk"/><stop offset="16%" class="dpul2nbgj"/><stop offset="20%" class="tg37v4tfl"/><stop offset="25%" class="u157b7b-l"/><stop offset="29.5%" class="faluwpbik"/><stop offset="35%" class="xke4xebyi"/><stop offset="39.5%" class="e19y8jsjz"/><stop offset="45%" class="wtyzjrbwk"/><stop offset="52.5%" class="hzp2u2_-r"/><stop offset="55.5%" class="mg2bqx4au"/><stop offset="59.5%" class="r_c0m1zgh"/><stop offset="64.5%" class="ubju6ob-j"/><stop offset="70%" class="ekudhhtho"/><stop offset="77%" class="l9rl_abuc"/><stop offset="85.5%" class="b4zjynl7o"/><stop offset="100%" class="fm6jqmkoj"/></radialGradient><path id="SVGW1kg9EdA" class="nviy0eumh"/></defs><mask id="SVG0h2J2dSX" class="n1mjunbsu"><use href="#SVGW1kg9EdA"/></mask><g mask="url(#SVG0h2J2dSX)"><path fill="url(#SVGL9CZzb2N)" class="xggahwb9k"/><path fill="url(#SVGyW8gxczB)" class="xggahwb9k"/><path fill="url(#SVG4pwrbdCB)" class="xggahwb9k"/><path fill="url(#SVGHRCAsbwa)" class="xggahwb9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:lovable-icon" {...props}></Icon>
<style>
:global(.a50azibyu) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.964;
}

:global(.b4zjynl7o) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.005;
}

:global(.bbijpbcqe) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.179;
}

:global(.bz2nbh6bo) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.876;
}

:global(.c6y42_gyr) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.336;
}

:global(.c7qxjz4xc) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.914;
}

:global(.ccb3h2b-r) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.103;
}

:global(.cj425sbmd) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.049;
}

:global(.cjn27pa5f) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.93;
}

:global(.dpul2nbgj) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.92;
}

:global(.e19y8jsjz) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.547;
}

:global(.e6723-b8l) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.866;
}

:global(.ekudhhtho) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.049;
}

:global(.eo-4m3-dp) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0;
}

:global(.epm5p4-sr) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.387;
}

:global(.f7-ean4-g) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.106;
}

:global(.faluwpbik) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.753;
}

:global(.fdnai5bpm) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.776;
}

:global(.fem56kbcc) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.635;
}

:global(.fm6jqmkoj) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0;
}

:global(.g9pcewb2x) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.959;
}

:global(.h096c3bpq) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.998;
}

:global(.h573bzbkh) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
}

:global(.h5owgwbla) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.141;
}

:global(.hzp2u2_-r) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.262;
}

:global(.idm0p2b6p) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.197;
}

:global(.ihv_n_b2c) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.972;
}

:global(.iznxipmlg) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.932;
}

:global(.j7n3rmbkg) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.005;
}

:global(.jv7r6gbwh) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.453;
}

:global(.k0qrvrche) {
  stop-color: var(--svg-color--ff0105, #ff0105);
}

:global(.k72_dmiob) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.995;
}

:global(.k7rh_ebdt) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.767;
}

:global(.kchlv0gcs) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.021;
}

:global(.kkh1ypb6l) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.022;
}

:global(.ky33i4bxn) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.983;
}

:global(.l9rl_abuc) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.019;
}

:global(.lil77pbyz) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.998;
}

:global(.loi85ac1q) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.02;
}

:global(.lxvp1_b8m) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.972;
}

:global(.mg2bqx4au) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.209;
}

:global(.mmi_d9b0k) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.049;
}

:global(.mz_wmfqco) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.817;
}

:global(.n1mjunbsu) {
  fill: var(--svg-color--fff, #fff);
}

:global(.n73wcjkkd) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.071;
}

:global(.na9h9nb7b) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.256;
}

:global(.nag_lxbvx) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.957;
}

:global(.nepzut_yk) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.937;
}

:global(.nmhantbyb) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.005;
}

:global(.nv85m5bop) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.624;
}

:global(.nviy0eumh) {
  d: path("M76.812 0c42.423 0 76.813 34.48 76.813 77.015v29.27h25.563c42.423 0 76.812 34.481 76.812 77.015s-34.39 77.015-76.812 77.015H0v-183.3C0 34.48 34.39 0 76.812 0");
}

:global(.ofh3ubddq) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.989;
}

:global(.oinsvpbpq) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.952;
}

:global(.oz8r6fb1c) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
}

:global(.plv_hzbmr) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.036;
}

:global(.pu6l-ebjo) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.059;
}

:global(.qsndi2b3f) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.244;
}

:global(.r_c0m1zgh) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.149;
}

:global(.rwykwco9p) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.126;
}

:global(.sfzo59b8s) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.73;
}

:global(.shuqpmb1r) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.765;
}

:global(.t7sxtwb5g) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.282;
}

:global(.tamj2ub2k) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0;
}

:global(.tg37v4tfl) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.885;
}

:global(.thorri0bf) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.705;
}

:global(.tsba924uk) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.611;
}

:global(.u157b7b-l) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.825;
}

:global(.ubju6ob-j) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.091;
}

:global(.urzwv28ey) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0;
}

:global(.uy4agtbrg) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.821;
}

:global(.v7rducuos) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.967;
}

:global(.vbeo9sbux) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.904;
}

:global(.wa6txjb6y) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.005;
}

:global(.wdum75b7p) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.886;
}

:global(.wh_2zyb_e) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.257;
}

:global(.wtyzjrbwk) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.419;
}

:global(.x3my7-tnb) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.36;
}

:global(.xggahwb9k) {
  d: path("M0 0h1567.207v266.649H0z");
}

:global(.xke4xebyi) {
  stop-color: var(--svg-color--fe7b02, #fe7b02);
  stop-opacity: 0.646;
}

:global(.xs03cac7x) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.991;
}

:global(.xy4iqmbal) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.821;
}

:global(.y0whgv90r) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.713;
}

:global(.y1xxxxb1b) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.103;
}

:global(.y4s2hccpv) {
  stop-color: var(--svg-color--ff66f4, #ff66f4);
  stop-opacity: 0.298;
}

:global(.zesg976so) {
  stop-color: var(--svg-color--4b73ff, #4b73ff);
  stop-opacity: 0.077;
}

:global(.zv5zsmbcx) {
  stop-color: var(--svg-color--ff0105, #ff0105);
  stop-opacity: 0.171;
}

</style>

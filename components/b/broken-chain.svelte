<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itMuche)" class="tynjixqsp"/><path fill="url(#iDJTzSb)" class="rjxz6ebmg"/><path fill="url(#iC74KTv)" class="m4kybzbci"/><path fill="url(#iCYTUKd)" class="rjxz6ebmg"/><path fill="url(#i6GOgYD)" class="rjxz6ebmg"/><path fill="url(#iERZ75c)" class="hiv37dbru"/><path fill="url(#iw9zCJd)" class="e77z0_iig"/><path fill="url(#i9zhkte)" class="im0ih4llc"/><path fill="url(#iWQF6Ab)" class="im0ih4llc"/><path fill="url(#i2NDAuc)" class="e77z0_iig"/><path fill="url(#iMFaxvc)" class="hh3uk3bvt"/><path fill="url(#iQJIIZD)" class="w16-pfbaw"/><path fill="url(#iyE5Uwc)" class="w16-pfbaw"/><path fill="url(#iQmXiZd)" class="w16-pfbaw"/><path fill="url(#iJMWzue)" class="sf7lc_bvx"/><path fill="url(#irhzc9d)" class="sf7lc_bvx"/><path fill="url(#ipdqNdb)" class="j_c6d_b1c"/><path fill="url(#iM8hvbc)" class="j_c6d_b1c"/><path fill="url(#ii5HVMd)" class="vrxz4kb-d"/><path fill="url(#iyg9VNb)" class="vrxz4kb-d"/><path fill="url(#ioqhRNg)" class="vo43evcuz"/><path fill="url(#iuENwVb)" class="vo43evcuz"/><path fill="url(#il6dJmc)" class="n6obu0b3w"/><path fill="url(#idaxPFd)" class="n6obu0b3w"/><path fill="url(#iG6W4Tc)" class="m49v9uihp"/><path fill="url(#ilUXWdX)" class="eohcx0baa"/><ellipse fill="url(#i0r6voe)" transform="rotate(45.156 16.982 15.228)" class="uezb0eb9v"/><path fill="url(#isxWKGb)" clip-rule="evenodd" class="fjmw2-cul"/><path fill="url(#i0KXZ6d)" clip-rule="evenodd" class="fjmw2-cul"/><defs><radialGradient id="itMuche" cx="0" cy="0" r="1" gradientTransform="matrix(-8.31251 16.37494 -12.81096 -6.5033 8.75 20.875)" gradientUnits="userSpaceOnUse"><stop class="v7n33ngej"/><stop offset=".366" class="hkq9astav"/><stop offset=".422" class="nayy4zb9e"/><stop offset=".557" class="e5f8376ao"/></radialGradient><radialGradient id="iDJTzSb" cx="0" cy="0" r="1" gradientTransform="rotate(135.953 .284 12.378)scale(4.65208 3.03628)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="utosdhbdp"/><stop offset=".587" class="daefndbwk"/><stop offset="1" class="u22ziobhf"/></radialGradient><radialGradient id="iC74KTv" cx="0" cy="0" r="1" gradientTransform="rotate(102.043 -.39 16.905)scale(4.79298 2.82048)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iCYTUKd" cx="0" cy="0" r="1" gradientTransform="rotate(138.323 .336 13.687)scale(6.86163 3.92411)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="lc70cxbti"/><stop offset="1" class="k7_uclb6f"/></radialGradient><radialGradient id="iERZ75c" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 2.8125 -1.65505 .66202 4 25.75)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iw9zCJd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.785 11.57805 -9.05807 -8.43763 24.063 8.25)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="yu0tdibhu"/><stop offset=".318" class="v1lpswbiz"/><stop offset=".365" class="bnl8cab8s"/><stop offset=".528" class="d954e0lcu"/></radialGradient><radialGradient id="i9zhkte" cx="0" cy="0" r="1" gradientTransform="matrix(7.875 .3125 -.23699 5.97214 20.563 15.188)" gradientUnits="userSpaceOnUse"><stop class="utosdhbdp"/><stop offset=".272" class="utosdhbdp"/><stop offset="1" class="u22ziobhf"/></radialGradient><radialGradient id="iWQF6Ab" cx="0" cy="0" r="1" gradientTransform="rotate(130.073 10.38 9.965)scale(5.14554 3.90221)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="koxrbb0yz"/><stop offset="1" class="ajp_oq2nu"/></radialGradient><radialGradient id="i2NDAuc" cx="0" cy="0" r="1" gradientTransform="matrix(5.8125 -2.375 1.80112 4.408 17.438 12.875)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="lc70cxbti"/><stop offset="1" class="k7_uclb6f"/></radialGradient><radialGradient id="iyE5Uwc" cx="0" cy="0" r="1" gradientTransform="rotate(53.867 -8.966 12.096)scale(5.96358 8.2978)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="g2_r7hbkc"/><stop offset=".437" class="wz2m95b9z"/></radialGradient><radialGradient id="iQmXiZd" cx="0" cy="0" r="1" gradientTransform="rotate(113.847 -.147 9.004)scale(2.28572)" gradientUnits="userSpaceOnUse"><stop class="h9rc_3orx"/><stop offset=".291" class="p83xvebjt"/></radialGradient><radialGradient id="irhzc9d" cx="0" cy="0" r="1" gradientTransform="matrix(3.71971 9.58096 -8.93837 3.47023 7.487 7.445)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="g2_r7hbkc"/><stop offset=".485" class="wz2m95b9z"/></radialGradient><radialGradient id="iM8hvbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.50283 7.66444 -4.56049 .89421 12.093 6.295)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="g2_r7hbkc"/><stop offset=".515" class="wz2m95b9z"/></radialGradient><radialGradient id="iyg9VNb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 -5.5438 4.5879 -.98272 20.969 25.512)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g2_r7hbkc"/><stop offset=".516" class="wz2m95b9z"/></radialGradient><radialGradient id="iuENwVb" cx="0" cy="0" r="1" gradientTransform="matrix(4.53125 6.28125 -4.21402 3.03996 25.625 22.906)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="g2_r7hbkc"/><stop offset=".553" class="wz2m95b9z"/></radialGradient><radialGradient id="idaxPFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53126 -3.21874 4.4786 -2.13062 26.25 19.219)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="g2_r7hbkc"/><stop offset=".515" class="wz2m95b9z"/></radialGradient><radialGradient id="iG6W4Tc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51691 7.55347 -3.42763 -3.41104 21.936 10.784)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="hkvpugxoe"/><stop offset=".657" class="yu0tdibhu"/></radialGradient><radialGradient id="ilUXWdX" cx="0" cy="0" r="1" gradientTransform="matrix(2.9375 3.1875 -6.02722 5.5545 17.75 10.313)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="v4wabqb3y"/><stop offset=".832" class="ajp_oq2nu"/></radialGradient><radialGradient id="isxWKGb" cx="0" cy="0" r="1" gradientTransform="matrix(-.18756 -7.05917 12.87636 -.34213 11.75 22.746)" gradientUnits="userSpaceOnUse"><stop class="epx7qbbtz"/><stop offset=".678" class="xhlnhyb9q"/></radialGradient><linearGradient id="i6GOgYD" x1="-5.188" x2="8.75" y1="9.75" y2="25" gradientUnits="userSpaceOnUse"><stop offset=".687" class="lc70cxbti"/><stop offset=".828" class="k7_uclb6f"/></linearGradient><linearGradient id="iMFaxvc" x1="7.5" x2="23.25" y1="-3.5" y2="10.5" gradientUnits="userSpaceOnUse"><stop offset=".566" class="lc70cxbti"/><stop offset=".866" class="k7_uclb6f"/></linearGradient><linearGradient id="iQJIIZD" x1="6.407" x2="4.257" y1="7.879" y2="15.087" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".53" class="pr8xmhb1a"/><stop offset=".561" class="pr8xmhb1a"/><stop offset=".584" class="pr8xmhb1a"/><stop offset=".714" class="qfxyd7plq"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="iJMWzue" x1="10.986" x2="4.991" y1="4.771" y2="10.71" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".511" class="pr8xmhb1a"/><stop offset=".535" class="pr8xmhb1a"/><stop offset=".559" class="pr8xmhb1a"/><stop offset=".705" class="bg6rdrb-r"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="ipdqNdb" x1="15.5" x2="8.833" y1="5" y2="7.289" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".511" class="pr8xmhb1a"/><stop offset=".535" class="pr8xmhb1a"/><stop offset=".559" class="pr8xmhb1a"/><stop offset=".714" class="df5lljdnb"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="ii5HVMd" x1="23.407" x2="17.095" y1="22.125" y2="24.234" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".511" class="pr8xmhb1a"/><stop offset=".535" class="pr8xmhb1a"/><stop offset=".559" class="pr8xmhb1a"/><stop offset=".714" class="cyhi1xbrn"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="ioqhRNg" x1="28.986" x2="22.991" y1="20.832" y2="26.771" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".511" class="pr8xmhb1a"/><stop offset=".535" class="pr8xmhb1a"/><stop offset=".559" class="pr8xmhb1a"/><stop offset=".705" class="bg6rdrb-r"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="il6dJmc" x1="27.381" x2="25.18" y1="14.78" y2="22.462" gradientUnits="userSpaceOnUse"><stop offset=".452" class="clj23bbae"/><stop offset=".511" class="pr8xmhb1a"/><stop offset=".535" class="pr8xmhb1a"/><stop offset=".559" class="pr8xmhb1a"/><stop offset=".714" class="cyhi1xbrn"/><stop offset=".753" class="i-sj6dg0y"/></linearGradient><linearGradient id="i0r6voe" x1="14.289" x2="20.723" y1="15.341" y2="15.461" gradientUnits="userSpaceOnUse"><stop offset=".195" class="kvqilrbta"/><stop offset=".669" class="cvrffzb8p"/></linearGradient><linearGradient id="i0KXZ6d" x1="6.08" x2="14.433" y1="13.323" y2="20.88" gradientUnits="userSpaceOnUse"><stop offset=".651" class="a9rrwypuh"/><stop offset=".863" class="k7_uclb6f"/></linearGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:broken-chain" {...props}></Icon>
<style>
:global(.a9rrwypuh) {
  stop-color: var(--svg-color--9b91a6, #9B91A6);
}

:global(.ajp_oq2nu) {
  stop-color: var(--svg-color--bfb5cb, #BFB5CB);
  stop-opacity: 0;
}

:global(.bg6rdrb-r) {
  stop-color: var(--svg-color--295cf7, #295CF7);
}

:global(.bnl8cab8s) {
  stop-color: var(--svg-color--e9e1f2, #E9E1F2);
}

:global(.clj23bbae) {
  stop-color: var(--svg-color--417aff, #417AFF);
}

:global(.cvrffzb8p) {
  stop-color: var(--svg-color--ad91c9, #AD91C9);
}

:global(.cyhi1xbrn) {
  stop-color: var(--svg-color--2e50ff, #2E50FF);
}

:global(.d954e0lcu) {
  stop-color: var(--svg-color--c3bfc6, #C3BFC6);
}

:global(.daefndbwk) {
  stop-color: var(--svg-color--b597d4, #B597D4);
  stop-opacity: 0.63;
}

:global(.df5lljdnb) {
  stop-color: var(--svg-color--4573ff, #4573FF);
}

:global(.e5f8376ao) {
  stop-color: var(--svg-color--c49fe7, #C49FE7);
}

:global(.e77z0_iig) {
  d: path("M21.016 3.54a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L20.272 8.75a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.eohcx0baa) {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("m16.004 13.959l2.25 2.249l3.925-3.926a1.59 1.59 0 0 0 0-2.25a1.59 1.59 0 0 0-2.249 0z");
}

:global(.epx7qbbtz) {
  stop-color: var(--svg-color--b789df, #B789DF);
}

:global(.fjmw2-cul) {
  fill-rule: evenodd;
  d: path("m15.374 19.051l.052-.048c.471-.468.35-1.353-.27-1.976c-.619-.623-1.503-.748-1.974-.28l-.042.045l-.002-.002l-3.244 3.244a1.59 1.59 0 0 0 0 2.249a1.595 1.595 0 0 0 2.249 0z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g2_r7hbkc) {
  stop-color: var(--svg-color--3453fc, #3453FC);
  stop-opacity: 0;
}

:global(.h9rc_3orx) {
  stop-color: var(--svg-color--6096ff, #6096FF);
}

:global(.hh3uk3bvt) {
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M21.016 3.54a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L20.272 8.75a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.hiv37dbru) {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M6.516 18.04a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L5.772 23.25a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.hkq9astav) {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

:global(.hkvpugxoe) {
  stop-color: var(--svg-color--e5e1e9, #E5E1E9);
}

:global(.i-sj6dg0y) {
  stop-color: var(--svg-color--6480f7, #6480F7);
}

:global(.im0ih4llc) {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M21.016 3.54a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L20.272 8.75a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.j_c6d_b1c) {
  d: path("M10.798 4.03a1 1 0 0 1 1.212.731l.96 2.965a1 1 0 1 1-1.94.488l-.96-2.965a1.005 1.005 0 0 1 .727-1.219");
}

:global(.k7_uclb6f) {
  stop-color: var(--svg-color--ada2bb, #ADA2BB);
  stop-opacity: 0;
}

:global(.koxrbb0yz) {
  stop-color: var(--svg-color--bfb5cb, #BFB5CB);
}

:global(.kvqilrbta) {
  stop-color: var(--svg-color--ad99c3, #AD99C3);
}

:global(.lc70cxbti) {
  stop-color: var(--svg-color--a196ad, #A196AD);
}

:global(.m49v9uihp) {
  d: path("m16.004 13.959l2.25 2.249l3.925-3.926a1.59 1.59 0 0 0 0-2.25a1.59 1.59 0 0 0-2.249 0z");
}

:global(.m4kybzbci) {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M6.516 18.04a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L5.772 23.25a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.n6obu0b3w) {
  d: path("M27.725 20.977a1.006 1.006 0 0 0 .55-1.933l-3.5-1.005a1.006 1.006 0 0 0-.55 1.933z");
}

:global(.nayy4zb9e) {
  stop-color: var(--svg-color--d0bee4, #D0BEE4);
}

:global(.p83xvebjt) {
  stop-color: var(--svg-color--4e8bff, #4E8BFF);
  stop-opacity: 0;
}

:global(.pr8xmhb1a) {
  stop-color: var(--svg-color--5291ff, #5291FF);
}

:global(.qfxyd7plq) {
  stop-color: var(--svg-color--3758fe, #3758FE);
}

:global(.rjxz6ebmg) {
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  d: path("M6.516 18.04a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L5.772 23.25a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.sf7lc_bvx) {
  d: path("M5.707 5.249a.996.996 0 0 0-1.414 0a1.01 1.01 0 0 0 0 1.421l4 4.02a.996.996 0 0 0 1.414 0a1.01 1.01 0 0 0 0-1.421z");
}

:global(.stui2mbih) {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

:global(.tynjixqsp) {
  d: path("M6.516 18.04a5.262 5.262 0 0 1 7.441 7.443l-2.976 2.976a5.263 5.263 0 0 1-7.44-7.442zm5.209 5.21a2.104 2.104 0 1 0-2.976-2.977L5.772 23.25a2.11 2.11 0 0 0 0 2.977a2.11 2.11 0 0 0 2.977 0z");
}

:global(.u22ziobhf) {
  stop-color: var(--svg-color--b597d4, #B597D4);
  stop-opacity: 0;
}

:global(.uezb0eb9v) {
  cx: 16.982px;
  cy: 15.228px;
  rx: 1.591px;
  ry: 0.996px;
}

:global(.utosdhbdp) {
  stop-color: var(--svg-color--b597d4, #B597D4);
}

:global(.v1lpswbiz) {
  stop-color: var(--svg-color--ece6f3, #ECE6F3);
}

:global(.v4wabqb3y) {
  stop-color: var(--svg-color--b1a7bd, #B1A7BD);
}

:global(.v7n33ngej) {
  stop-color: var(--svg-color--e2dbe9, #E2DBE9);
}

:global(.vc--wpv5i) {
  stop-color: var(--svg-color--fff, #fff);
}

:global(.vo43evcuz) {
  d: path("M23.707 21.31a.996.996 0 0 0-1.414 0a1.01 1.01 0 0 0 0 1.42l4 4.021a.996.996 0 0 0 1.414 0a1.01 1.01 0 0 0 0-1.421z");
}

:global(.vrxz4kb-d) {
  d: path("M21.203 27.97a1 1 0 0 1-1.213-.732l-.96-2.964a1 1 0 1 1 1.94-.488l.96 2.965a1.005 1.005 0 0 1-.727 1.219");
}

:global(.w16-pfbaw) {
  d: path("M4.275 11.023a1.006 1.006 0 0 0-.55 1.933l3.5 1.005a1.006 1.006 0 0 0 .55-1.933z");
}

:global(.wz2m95b9z) {
  stop-color: var(--svg-color--3a53f9, #3A53F9);
}

:global(.xhlnhyb9q) {
  stop-color: var(--svg-color--dad2e2, #DAD2E2);
}

:global(.yu0tdibhu) {
  stop-color: var(--svg-color--dcc5f5, #DCC5F5);
}

</style>

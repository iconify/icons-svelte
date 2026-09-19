<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8h7RHd)"><path fill="url(#igEqRlx)" class="cbt3z_bte"/></g><g filter="url(#imiQeSd)"><path fill="url(#iZXSJ2c)" class="dp5zn03wv"/></g><path fill="url(#ikznkZc)" class="ey5zbgbjp"/><path fill="url(#ilgrvSd)" class="ey5zbgbjp"/><g filter="url(#iEHiYrb)"><path fill="url(#i34FQ2U)" class="pcmf0ubff"/></g><g filter="url(#iO5ykFm)"><path fill="url(#iF7elCc)" class="z8m4ojbsq"/></g><g filter="url(#ix0fS3c)"><path fill="url(#iN8BIqd)" class="i1jvpn3uk"/></g><g filter="url(#irGIhtc)"><path fill="url(#iDBgMtd)" class="tjv3r76wo"/></g><g filter="url(#iU1sadd)"><path fill="url(#ic6dNtd)" class="zza_wacry"/></g><g filter="url(#i8BpI2d)"><path stroke="url(#iziRrTc)" class="pc1zn2bqe"/></g><g filter="url(#ilxnocc)"><path stroke="url(#iXWBYUc)" class="bm275k9lc"/></g><path fill="url(#idST5pu)" class="hqysw8pcx"/><path fill="url(#im86CRd)" class="hqysw8pcx"/><path fill="url(#iCPpnyc)" class="hqysw8pcx"/><g filter="url(#ilL34ad)"><path stroke="url(#icmPooe)" class="evrhpbtoy"/></g><g filter="url(#iszkcNd)"><path stroke="url(#iopSBwB)" class="vtnfytbbg"/></g><g filter="url(#iwpKgkd)"><path stroke="url(#i0WUufc)" class="kxx4nwbuq"/></g><g filter="url(#i4GIxKd)"><path stroke="url(#i3mhl9c)" class="h01g-ob_b"/></g><g filter="url(#in52Unb)"><path stroke="url(#i6tZUOb)" class="jpx55qita"/></g><g filter="url(#iSoopjd)"><path fill="url(#iNG1zsb)" clip-rule="evenodd" class="enrje5b6a"/></g><path fill="url(#iq4ugPb)" clip-rule="evenodd" class="enrje5b6a"/><path fill="url(#iM0JX5d)" clip-rule="evenodd" class="enrje5b6a"/><path fill="url(#izkmkDc)" clip-rule="evenodd" class="enrje5b6a"/><g filter="url(#ijB0uzc)" class="gvkoecj5g"><path stroke="url(#iUnBrNc)" class="z2issgnve"/><path stroke="url(#iQAlLob)" class="z2issgnve"/><path stroke="url(#i9cf0nb)" class="z2issgnve"/></g><g filter="url(#iUgacke)"><path stroke="url(#iW4JBCc)" class="glub32b3e"/></g><g filter="url(#iI6CYib)"><path stroke="url(#iduV7Wc)" class="sj-ma5puw"/></g><g filter="url(#i1p2e6c)"><path stroke="url(#i7lUR1d)" class="cjc61ubxe"/></g><g filter="url(#i3X3POD)"><path stroke="url(#iKpVWUc)" class="skw63zxaf"/></g><defs><linearGradient id="iZXSJ2c" x1="2" x2="13.46" y1="14.688" y2="5.313" gradientUnits="userSpaceOnUse"><stop offset=".006" class="vl0r3wdwu"/><stop offset="1" class="r1z9orbzd"/></linearGradient><linearGradient id="ikznkZc" x1="13.058" x2="16.3" y1="31.179" y2="20.032" gradientUnits="userSpaceOnUse"><stop class="fgnjdwbcj"/><stop offset="1" class="qge692bsq"/></linearGradient><linearGradient id="ilgrvSd" x1="15.628" x2="15.628" y1="30.665" y2="28.807" gradientUnits="userSpaceOnUse"><stop class="u8nbbee8a"/><stop offset="1" class="ju8yyqb5p"/></linearGradient><linearGradient id="i34FQ2U" x1="7.208" x2="19.951" y1="18.055" y2="27.823" gradientUnits="userSpaceOnUse"><stop class="bjcpslb6a"/><stop offset="1" class="lr3rzubwp"/></linearGradient><linearGradient id="iF7elCc" x1="11.951" x2="12.782" y1="22.838" y2="21.139" gradientUnits="userSpaceOnUse"><stop class="o_frnwzgl"/><stop offset="1" class="wd_h3qrnn"/></linearGradient><linearGradient id="iN8BIqd" x1="22.901" x2="30.332" y1="17.452" y2="10.969" gradientUnits="userSpaceOnUse"><stop offset=".006" class="cuc-5ab1p"/><stop offset="1" class="kjlr08bps"/></linearGradient><linearGradient id="iDBgMtd" x1="14.829" x2="29.026" y1="12.692" y2="5.662" gradientUnits="userSpaceOnUse"><stop class="nwj5nccpv"/><stop offset="1" class="gcrxte2lo"/></linearGradient><linearGradient id="ic6dNtd" x1="15.78" x2="27.513" y1="12.154" y2="6.345" gradientUnits="userSpaceOnUse"><stop class="h_p9fobgm"/><stop offset="1" class="v8y3az_-b"/></linearGradient><linearGradient id="iziRrTc" x1="15.977" x2="14.114" y1="9.777" y2="10.242" gradientUnits="userSpaceOnUse"><stop offset=".809" class="chsg0ma5r"/><stop offset="1" class="ofy0k6bns"/></linearGradient><linearGradient id="iXWBYUc" x1="24.406" x2="28.396" y1="12.375" y2="11.516" gradientUnits="userSpaceOnUse"><stop class="iukvg-b_r"/><stop offset="1" class="f3k1m9bfd"/></linearGradient><linearGradient id="idST5pu" x1="28.888" x2="18.826" y1="5.008" y2="10.349" gradientUnits="userSpaceOnUse"><stop class="mi67r7bqq"/><stop offset="1" class="m3-bw1g4c"/></linearGradient><linearGradient id="icmPooe" x1="16.414" x2="29.118" y1="12.561" y2="14.524" gradientUnits="userSpaceOnUse"><stop class="eydyn-bol"/><stop offset="1" class="e_dkudbme"/></linearGradient><linearGradient id="iopSBwB" x1="30.787" x2="27.111" y1="8.292" y2="16.178" gradientUnits="userSpaceOnUse"><stop class="jfxiz08at"/><stop offset="1" class="m64jy2bkj"/></linearGradient><linearGradient id="i0WUufc" x1="21.745" x2="22.45" y1="16.81" y2="15.167" gradientUnits="userSpaceOnUse"><stop class="z_ct39efo"/><stop offset="1" class="m64jy2bkj"/></linearGradient><linearGradient id="i3mhl9c" x1="24.62" x2="15.845" y1="27.78" y2="18.411" gradientUnits="userSpaceOnUse"><stop class="y9q3urb1p"/><stop offset="1" class="ee_vav3kn"/></linearGradient><linearGradient id="iNG1zsb" x1="5.864" x2="20.893" y1="15.447" y2="26.589" gradientUnits="userSpaceOnUse"><stop class="chce4754f"/><stop offset="1" class="u5k3d1_5a"/></linearGradient><linearGradient id="iq4ugPb" x1="20.442" x2="18.276" y1="26.745" y2="25.566" gradientUnits="userSpaceOnUse"><stop class="e96yduldd"/><stop offset="1" class="nkif2xbxu"/></linearGradient><linearGradient id="iQAlLob" x1="19.541" x2="7.05" y1="24.894" y2="18.016" gradientUnits="userSpaceOnUse"><stop class="xt1t4fcco"/><stop offset="1" class="v2vc85bfx"/></linearGradient><linearGradient id="i9cf0nb" x1="10.687" x2="7.129" y1="12.561" y2="17.384" gradientUnits="userSpaceOnUse"><stop class="xt1t4fcco"/><stop offset="1" class="v2vc85bfx"/></linearGradient><linearGradient id="iW4JBCc" x1="2.383" x2="6.747" y1="15.841" y2="8.144" gradientUnits="userSpaceOnUse"><stop class="bnlemd6gr"/><stop offset="1" class="zew6ygbtr"/></linearGradient><linearGradient id="iduV7Wc" x1="13.294" x2="7.62" y1="5.704" y2="7.688" gradientUnits="userSpaceOnUse"><stop class="bnlemd6gr"/><stop offset="1" class="zew6ygbtr"/></linearGradient><linearGradient id="i7lUR1d" x1="16.788" x2="14.931" y1="2.503" y2="4.803" gradientUnits="userSpaceOnUse"><stop class="at-nlehnh"/><stop offset="1" class="zew6ygbtr"/></linearGradient><linearGradient id="iKpVWUc" x1="3.91" x2="8.723" y1="6.061" y2="5.334" gradientUnits="userSpaceOnUse"><stop class="at-nlehnh"/><stop offset="1" class="zew6ygbtr"/></linearGradient><filter id="i8h7RHd" width="13.142" height="4.62" x="3.8" y="1.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.733333 0 0 0 0 0.847059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7988"/></filter><filter id="imiQeSd" width="11.46" height="11.61" x="2" y="4.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.720229 0 0 0 0 0.669826 0 0 0 0 0.795833 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7988"/></filter><filter id="iEHiYrb" width="19.399" height="13.427" x="5.315" y="16.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".5"/></filter><filter id="iO5ykFm" width="15.233" height="10.401" x="5.929" y="17.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".5"/></filter><filter id="ix0fS3c" width="7.69" height="7.85" x="22.31" y="9.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.690196 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7988"/></filter><filter id="irGIhtc" width="13.59" height="9.5" x="14.41" y="4.48" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.654902 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7988"/></filter><filter id="iU1sadd" width="13.126" height="8.648" x="14.642" y="5.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".25"/></filter><filter id="i8BpI2d" width="4.75" height="7.766" x="14.217" y="6.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".2"/></filter><filter id="ilxnocc" width="6.279" height="8.452" x="21.753" y="5.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".3"/></filter><filter id="ilL34ad" width="9.703" height="9.219" x="18.352" y="2.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".125"/></filter><filter id="iszkcNd" width="3.981" height="6.411" x="26.04" y="9.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".1"/></filter><filter id="iwpKgkd" width="5.215" height="2.163" x="22.334" y="14.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".1"/></filter><filter id="i4GIxKd" width="9.211" height="12.017" x="15.865" y="17.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".3"/></filter><filter id="in52Unb" width="10.129" height="9.813" x="5.531" y="19.652" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".5"/></filter><filter id="iSoopjd" width="15.642" height="14.823" x="5" y="11.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.529412 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7988"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.670588 0 0 0 0 0.392157 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_7988" result="effect2_innerShadow_28327_7988"/></filter><filter id="ijB0uzc" width="14.821" height="13.457" x="5.747" y="12.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".25"/></filter><filter id="iUgacke" width="4.223" height="8.785" x="2.225" y="7.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".125"/></filter><filter id="iI6CYib" width="7.753" height="3.289" x="5.698" y="5.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".125"/></filter><filter id="i1p2e6c" width="5.928" height="1.28" x="11.074" y="2.061" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".125"/></filter><filter id="i3X3POD" width="4.619" height="3.408" x="3.992" y="3.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7988" stdDeviation=".125"/></filter><radialGradient id="igEqRlx" cx="0" cy="0" r="1" gradientTransform="matrix(-.31742 -1.30934 8.71853 -2.11358 10.14 3.66)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="efh9illsq"/><stop offset="1" class="y5e3ycsif"/></radialGradient><radialGradient id="im86CRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.49998 .32812 -.33496 -.5104 28 2.39)" gradientUnits="userSpaceOnUse"><stop class="tzse7lmmt"/><stop offset="1" class="qmaudt5ke"/></radialGradient><radialGradient id="iCPpnyc" cx="0" cy="0" r="1" gradientTransform="matrix(.588 .4694 -.58842 .73708 26.547 5.174)" gradientUnits="userSpaceOnUse"><stop class="crssjzypp"/><stop offset="1" class="gyep_4udh"/></radialGradient><radialGradient id="i6tZUOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.35995 -4.07146 4.021 3.31831 9.429 25.566)" gradientUnits="userSpaceOnUse"><stop class="y9q3urb1p"/><stop offset="1" class="ee_vav3kn"/></radialGradient><radialGradient id="iM0JX5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.33484 .57317 -5.13139 -2.9977 12.721 20.17)" gradientUnits="userSpaceOnUse"><stop class="ir5r3es_r"/><stop offset="1" class="f1c4qhbhx"/></radialGradient><radialGradient id="izkmkDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67187 -.03125 .03311 -.71197 19.938 25.313)" gradientUnits="userSpaceOnUse"><stop class="p0n0de_8r"/><stop offset="1" class="n89y8qb3m"/></radialGradient><radialGradient id="iUnBrNc" cx="0" cy="0" r="1" gradientTransform="matrix(2.56937 -1.81832 1.44181 2.03734 7.01 17.818)" gradientUnits="userSpaceOnUse"><stop class="razhoxbge"/><stop offset="1" class="k8ifybcpn"/></radialGradient></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:leaf-fluttering-in-wind" {...props}></Icon>
<style>
:global(.at-nlehnh) {
  stop-color: var(--svg-color--e2d9f0, #E2D9F0);
  stop-opacity: 0.6;
}

:global(.bjcpslb6a) {
  stop-color: var(--svg-color--4bbc85, #4BBC85);
}

:global(.bm275k9lc) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M22.653 12.73c1.865-.897 4.596-3.236 4.475-6.652");
}

:global(.bnlemd6gr) {
  stop-color: var(--svg-color--dcd2ea, #DCD2EA);
}

:global(.cbt3z_bte) {
  d: path("M4.45 6.52a.47.47 0 0 1-.35-.15c-.2-.2-.2-.51 0-.71C6.47 3.3 9.61 2 12.96 2c1.23 0 2.46.18 3.63.54a.5.5 0 0 1 .33.62c-.08.27-.36.42-.62.33A11.8 11.8 0 0 0 12.96 3C9.88 3 6.98 4.2 4.81 6.38c-.1.1-.23.14-.36.14");
}

:global(.chce4754f) {
  stop-color: var(--svg-color--269c64, #269C64);
}

:global(.chsg0ma5r) {
  stop-color: var(--svg-color--84d59e, #84D59E);
}

:global(.cjc61ubxe) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.627 2.966c-.926-.245-3.258-.682-5.178-.476");
}

:global(.crssjzypp) {
  stop-color: var(--svg-color--60a576, #60A576);
}

:global(.cuc-5ab1p) {
  stop-color: var(--svg-color--c2b4d9, #C2B4D9);
}

:global(.dp5zn03wv) {
  d: path("M2.5 16.48c-.28 0-.5-.22-.5-.5C2 9.94 6.92 5.02 12.96 5.02c.28 0 .5.22.5.5s-.22.5-.5.5C7.47 6.02 3 10.49 3 15.98c0 .28-.22.5-.5.5");
}

:global(.e_dkudbme) {
  stop-color: var(--svg-color--5bb180, #5BB180);
}

:global(.e96yduldd) {
  stop-color: var(--svg-color--32c37e, #32C37E);
}

:global(.ee_vav3kn) {
  stop-color: var(--svg-color--6cc995, #6CC995);
  stop-opacity: 0;
}

:global(.efh9illsq) {
  stop-color: var(--svg-color--cbbddc, #CBBDDC);
}

:global(.enrje5b6a) {
  fill-rule: evenodd;
  d: path("M6.1 12.173a1.1 1.1 0 0 1 1.1 1.1v3.624a.9.9 0 0 0 .452.78l12.237 7.014a1.1 1.1 0 1 1-1.094 1.908L6.56 19.586A3.1 3.1 0 0 1 5 16.896v-3.623a1.1 1.1 0 0 1 1.1-1.1");
}

:global(.evrhpbtoy) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.727 10.969l7.921-4.385a2 2 0 0 0 1.032-1.75V2.5");
}

:global(.ey5zbgbjp) {
  d: path("M5 16.01v2.87c0 6.15 4.99 11.14 11.14 11.14h7.64c.69 0 1.25-.56 1.25-1.25v-.63c0-6.15-4.99-11.14-11.14-11.14H6z");
}

:global(.eydyn-bol) {
  stop-color: var(--svg-color--53cd8b, #53CD8B);
}

:global(.f1c4qhbhx) {
  stop-color: var(--svg-color--23a965, #23A965);
  stop-opacity: 0;
}

:global(.f3k1m9bfd) {
  stop-color: var(--svg-color--63d393, #63D393);
}

:global(.fgnjdwbcj) {
  stop-color: var(--svg-color--459589, #459589);
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gcrxte2lo) {
  stop-color: var(--svg-color--4dbf82, #4DBF82);
}

:global(.glub32b3e) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M2.601 15.96c-.026-1.684.695-5.872 3.472-8.034");
}

:global(.gvkoecj5g) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

:global(.gyep_4udh) {
  stop-color: var(--svg-color--60a576, #60A576);
  stop-opacity: 0;
}

:global(.h_p9fobgm) {
  stop-color: var(--svg-color--4fc886, #4FC886);
}

:global(.h01g-ob_b) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M16.715 18.411c2.49.62 7.479 3.55 7.51 10.317");
}

:global(.hqysw8pcx) {
  d: path("M18.43 11.41c.08 0 .17-.02.24-.06l8.08-4.41C27.52 6.51 28 5.71 28 4.83v-2.3c0-.28-.23-.51-.51-.51s-.51.23-.51.51v2.29c0 .51-.28.97-.72 1.22l-8.08 4.41c-.25.13-.34.44-.2.69c.09.17.27.27.45.27");
}

:global(.i1jvpn3uk) {
  d: path("M22.81 16.93c-.28 0-.5-.22-.5-.5s.22-.5.5-.5c1.28 0 2.51-.39 3.56-1.12A6.25 6.25 0 0 0 29 9.73c0-.28.22-.5.5-.5s.5.23.5.5c0 2.34-1.14 4.54-3.06 5.89a7.1 7.1 0 0 1-4.13 1.31");
}

:global(.ir5r3es_r) {
  stop-color: var(--svg-color--23a965, #23A965);
}

:global(.iukvg-b_r) {
  stop-color: var(--svg-color--63d393, #63D393);
  stop-opacity: 0;
}

:global(.jfxiz08at) {
  stop-color: var(--svg-color--dbd8e4, #DBD8E4);
}

:global(.jpx55qita) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.78 20.902c.33 1.99 2.317 6.237 7.63 7.312");
}

:global(.ju8yyqb5p) {
  stop-color: var(--svg-color--528289, #528289);
  stop-opacity: 0;
}

:global(.k8ifybcpn) {
  stop-color: var(--svg-color--62b78c, #62B78C);
  stop-opacity: 0;
}

:global(.kjlr08bps) {
  stop-color: var(--svg-color--c8c4d5, #C8C4D5);
}

:global(.kxx4nwbuq) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M22.634 16.554c.922.026 3.081-.313 4.615-1.562");
}

:global(.lr3rzubwp) {
  stop-color: var(--svg-color--46af84, #46AF84);
}

:global(.m3-bw1g4c) {
  stop-color: var(--svg-color--34c075, #34C075);
}

:global(.m64jy2bkj) {
  stop-color: var(--svg-color--dbd8e4, #DBD8E4);
  stop-opacity: 0;
}

:global(.mi67r7bqq) {
  stop-color: var(--svg-color--269d63, #269D63);
}

:global(.n89y8qb3m) {
  stop-color: var(--svg-color--65d69c, #65D69C);
  stop-opacity: 0;
}

:global(.nkif2xbxu) {
  stop-color: var(--svg-color--32c37e, #32C37E);
  stop-opacity: 0;
}

:global(.nwj5nccpv) {
  stop-color: var(--svg-color--4fc679, #4FC679);
}

:global(.o_frnwzgl) {
  stop-color: var(--svg-color--33a171, #33A171);
}

:global(.ofy0k6bns) {
  stop-color: var(--svg-color--84d49e, #84D49E);
  stop-opacity: 0;
}

:global(.p0n0de_8r) {
  stop-color: var(--svg-color--65d69c, #65D69C);
}

:global(.pc1zn2bqe) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.467 6.578c-1.198.635-3.61 2.656-3.75 6.765");
}

:global(.pcmf0ubff) {
  d: path("M6.315 17.302v2.34c0 5.016 4.335 9.086 9.677 9.086h6.637c.6 0 1.086-.457 1.086-1.02v-.513c0-5.016-4.335-9.086-9.677-9.086H7.184z");
}

:global(.qge692bsq) {
  stop-color: var(--svg-color--5ab57a, #5AB57A);
}

:global(.qmaudt5ke) {
  stop-color: var(--svg-color--66b386, #66B386);
  stop-opacity: 0;
}

:global(.r1z9orbzd) {
  stop-color: var(--svg-color--cabddd, #CABDDD);
}

:global(.razhoxbge) {
  stop-color: var(--svg-color--62b78c, #62B78C);
}

:global(.sj-ma5puw) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.076 5.386c-2.639 0-5.277.953-7.003 2.54");
}

:global(.skw63zxaf) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.367 6.06c.542-.6 2.075-1.975 3.868-2.657");
}

:global(.tjv3r76wo) {
  d: path("M28 4.48v1.95a7.55 7.55 0 0 1-7.55 7.55h-5.19a.85.85 0 0 1-.85-.85v-.43c0-4.17 3.38-7.7 7.55-7.7h5.35z");
}

:global(.tzse7lmmt) {
  stop-color: var(--svg-color--66b386, #66B386);
}

:global(.u5k3d1_5a) {
  stop-color: var(--svg-color--45c68e, #45C68E);
}

:global(.u8nbbee8a) {
  stop-color: var(--svg-color--528289, #528289);
}

:global(.v2vc85bfx) {
  stop-color: var(--svg-color--69d79e, #69D79E);
  stop-opacity: 0;
}

:global(.v8y3az_-b) {
  stop-color: var(--svg-color--4ebd8e, #4EBD8E);
}

:global(.vl0r3wdwu) {
  stop-color: var(--svg-color--ccc3d9, #CCC3D9);
}

:global(.vtnfytbbg) {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M29.72 9.735c.04 1.199-.653 4.328-3.38 5.81");
}

:global(.wd_h3qrnn) {
  stop-color: var(--svg-color--3fb774, #3FB774);
}

:global(.xt1t4fcco) {
  stop-color: var(--svg-color--69d79e, #69D79E);
}

:global(.y5e3ycsif) {
  stop-color: var(--svg-color--d2ccdb, #D2CCDB);
}

:global(.y9q3urb1p) {
  stop-color: var(--svg-color--6cc995, #6CC995);
}

:global(.z_ct39efo) {
  stop-color: var(--svg-color--dbd8e4, #DBD8E4);
  stop-opacity: 0.5;
}

:global(.z2issgnve) {
  d: path("M6.497 13.273v3.515a2 2 0 0 0 1.043 1.756l12.278 6.686");
}

:global(.z8m4ojbsq) {
  d: path("M18.121 26.48L7.558 20.56a1.231 1.231 0 0 1 1.18-2.162l10.696 5.675a1.37 1.37 0 1 1-1.313 2.407");
}

:global(.zew6ygbtr) {
  stop-color: var(--svg-color--dcd2ea, #DCD2EA);
  stop-opacity: 0;
}

:global(.zza_wacry) {
  d: path("m27.268 5.57l-.603 1.206c0 3.447-2.794 6.443-6.24 6.443h-4.58a.7.7 0 0 1-.703-.703v-.355c0-3.446 3.085-6.364 6.531-6.364l4.992.083z");
}

</style>

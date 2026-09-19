<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iwqEwNe)"><path class="a5t0acpmm"/><path fill="url(#iiL5oad)" class="xfe801bjy"/></g><path fill="url(#iVDqhIb)" class="jho8eud8h"/><path fill="url(#iF1rPob)" class="jho8eud8h"/><path fill="url(#iZ3jO7b)" class="jho8eud8h"/><path fill="url(#igKQGNe)" class="jho8eud8h"/><path fill="url(#iA6xrJc)" class="jho8eud8h"/><path fill="url(#ia8NoQb)" class="st_qpu9rb"/><path fill="url(#ilm9zMP)" class="st_qpu9rb"/><path fill="url(#ibzflhb)" class="st_qpu9rb"/><path fill="url(#iZZaqMc)" class="st_qpu9rb"/><path fill="url(#in6lQGE)" class="aoragubsy"/><path fill="url(#i1lBjsc)" class="aoragubsy"/><path fill="url(#ifq2Fud)" class="aoragubsy"/><path fill="url(#i9etLHb)" class="aoragubsy"/><path fill="url(#ikeP80l)" class="y2k63wbop"/><path fill="url(#i94TFXd)" class="y2k63wbop"/><path fill="url(#i2GUHyc)" class="y2k63wbop"/><path fill="url(#iCXm81L)" class="y2k63wbop"/><g filter="url(#i7duMlk)"><path class="a4vvbpb0h"/><path fill="url(#iXqxrae)" class="s1wtvyk-s"/></g><path fill="url(#ioF7Nsc)" class="s1wtvyk-s"/><path fill="url(#iynjbFe)" class="s1wtvyk-s"/><path fill="url(#ixjaBcc)" class="s1wtvyk-s"/><rect fill="url(#ipMsD1v)" class="kree96-eo"/><rect fill="url(#ilUtaGe)" class="kree96-eo"/><rect fill="url(#i58EvOc)" class="kree96-eo"/><rect fill="url(#iC22ZFb)" class="kree96-eo"/><rect fill="url(#iTWJd9c)" class="kree96-eo"/><rect fill="url(#ipOFPIN)" class="kree96-eo"/><rect fill="url(#iFR2kic)" class="kree96-eo"/><g filter="url(#ih6J9ze)"><path fill="url(#iKd7FZf)" class="v35k4mqxr"/></g><g filter="url(#iikPLbb)"><rect fill="url(#iRwKvsc)" class="ti-l9wb-i"/></g><g filter="url(#iULBnab)"><rect fill="url(#iz1L2nt)" class="biwzbgssn"/></g><g filter="url(#iSzwjob)"><path class="ttxd5bc4l"/></g><defs><radialGradient id="iiL5oad" cx="0" cy="0" r="1" gradientTransform="matrix(3.22822 9.08798 -11.67443 4.14698 23 11.812)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="orzf3j5tv"/><stop offset="1" class="u2yybui2i"/></radialGradient><radialGradient id="iVDqhIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.18707 4.77018 0 12.39 26.88)" gradientUnits="userSpaceOnUse"><stop class="uwho15b0m"/><stop offset="1" class="p1rx_0v1l"/></radialGradient><radialGradient id="igKQGNe" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.3466 -6.91977 0 11.63 17.347)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="axy2xmscy"/><stop offset="1" class="e7a3kpxov"/></radialGradient><radialGradient id="iA6xrJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.74168 6.33423 0 11.63 23.958)" gradientUnits="userSpaceOnUse"><stop offset=".822" class="cbqhmti7m"/><stop offset=".987" class="jq6js4_zj"/></radialGradient><radialGradient id="ia8NoQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.7595 7.31603 0 6.188 27.29)" gradientUnits="userSpaceOnUse"><stop class="ypxhk30rd"/><stop offset="1" class="tm7g5gbnk"/></radialGradient><radialGradient id="ibzflhb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.42709 -6.45029 0 5.263 18.23)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="oqyj8fbpq"/><stop offset="1" class="sqo2_1jyr"/></radialGradient><radialGradient id="i1lBjsc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.66527 0 0 -6.70115 21.267 23.27)" gradientUnits="userSpaceOnUse"><stop class="in55c-phu"/><stop offset="1" class="z7y5oc_4f"/></radialGradient><radialGradient id="ikeP80l" cx="0" cy="0" r="1" gradientTransform="rotate(-92.104 24.601 -1.873)scale(13.2673 7.2243)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="zfckbmbwq"/><stop offset="1" class="djv207hfo"/></radialGradient><radialGradient id="i94TFXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.81896 .74113 0 21.252 22.717)" gradientUnits="userSpaceOnUse"><stop offset=".141" class="spq9hx54c"/><stop offset="1" class="q2wcuxbjh"/></radialGradient><radialGradient id="i2GUHyc" cx="0" cy="0" r="1" gradientTransform="matrix(3.2452 3.784 -11.4046 9.78069 20.912 14.921)" gradientUnits="userSpaceOnUse"><stop class="g0z8bj9rv"/><stop offset="1" class="flh1x0chi"/></radialGradient><radialGradient id="iCXm81L" cx="0" cy="0" r="1" gradientTransform="matrix(1.7611 -6.01353 6.78822 1.98797 26.324 24.611)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="qh725-jas"/><stop offset=".508" class="z79i4z1bd"/></radialGradient><radialGradient id="iXqxrae" cx="0" cy="0" r="1" gradientTransform="matrix(6.04842 0 0 1.15509 23.113 21.989)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="e02h3gx5p"/><stop offset="1" class="wo80wzy-e"/></radialGradient><radialGradient id="ioF7Nsc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7592 0 0 -9.5527 26.697 26.062)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="f1wqexb4i"/><stop offset="1" class="c98-5wb0k"/></radialGradient><radialGradient id="iynjbFe" cx="0" cy="0" r="1" gradientTransform="matrix(.54129 1.709 -.78538 .24875 15.128 27.526)" gradientUnits="userSpaceOnUse"><stop class="eqw2qbtwv"/><stop offset="1" class="apn126baj"/></radialGradient><radialGradient id="ixjaBcc" cx="0" cy="0" r="1" gradientTransform="rotate(27.571 -35.389 43.099)scale(15.2369 14.2418)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="amlgsl62b"/><stop offset="1" class="i3mt4q-ni"/></radialGradient><radialGradient id="ipMsD1v" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.61197 -8.63989 0 28.234 10.079)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="yicrqm3hs"/><stop offset=".453" class="so-u2ccpu"/></radialGradient><radialGradient id="ilUtaGe" cx="0" cy="0" r="1" gradientTransform="matrix(-9.83928 0 0 -9.61491 28.84 10.461)" gradientUnits="userSpaceOnUse"><stop offset=".576" class="qhj2xybpu"/><stop offset="1" class="mj_l97mnq"/></radialGradient><radialGradient id="i58EvOc" cx="0" cy="0" r="1" gradientTransform="matrix(.57253 -5.28003 7.61746 .82599 23.738 15.303)" gradientUnits="userSpaceOnUse"><stop class="ljh4ujb0d"/><stop offset="1" class="q-hyakboh"/></radialGradient><radialGradient id="iC22ZFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.875 -10.8823 0 24.82 6.235)" gradientUnits="userSpaceOnUse"><stop offset=".689" class="s8hogcyqx"/><stop offset=".895" class="zrq_ottju"/></radialGradient><radialGradient id="iTWJd9c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46077 0 0 -13.4107 27.11 10.461)" gradientUnits="userSpaceOnUse"><stop offset=".835" class="vbn2g9bgm"/><stop offset="1" class="wdlwig3ok"/></radialGradient><radialGradient id="ipOFPIN" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.96323 -2.65156 0 24.82 4.397)" gradientUnits="userSpaceOnUse"><stop class="f8_uxtbzc"/><stop offset="1" class="cvydsjbla"/></radialGradient><radialGradient id="iFR2kic" cx="0" cy="0" r="1" gradientTransform="rotate(-45 27.501 -18.781)scale(11.6673)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="mqtzx-bbp"/><stop offset="1" class="q4u0j--_f"/></radialGradient><linearGradient id="iF1rPob" x1="8.511" x2="12.011" y1="21.014" y2="21.014" gradientUnits="userSpaceOnUse"><stop class="pnbzzm19n"/><stop offset="1" class="yl2s6groo"/></linearGradient><linearGradient id="iZ3jO7b" x1="14.418" x2="13.27" y1="22.006" y2="22.006" gradientUnits="userSpaceOnUse"><stop class="s3aos1w9p"/><stop offset="1" class="h7--h-bqa"/></linearGradient><linearGradient id="ilm9zMP" x1="8.865" x2="6.582" y1="22.974" y2="22.974" gradientUnits="userSpaceOnUse"><stop class="umkj4bzfu"/><stop offset="1" class="eca4lvb3u"/></linearGradient><linearGradient id="iZZaqMc" x1="8.654" x2="8.069" y1="16.495" y2="17.552" gradientUnits="userSpaceOnUse"><stop class="n0nwenbpt"/><stop offset="1" class="uin3tjbzk"/></linearGradient><linearGradient id="in6lQGE" x1="14.307" x2="19.349" y1="23.566" y2="23.566" gradientUnits="userSpaceOnUse"><stop class="as0itkbft"/><stop offset="1" class="fr04q5b2f"/></linearGradient><linearGradient id="ifq2Fud" x1="14.27" x2="15.158" y1="16.532" y2="18.013" gradientUnits="userSpaceOnUse"><stop class="jggu3dbyd"/><stop offset="1" class="szp84gm2l"/></linearGradient><linearGradient id="i9etLHb" x1="15.394" x2="15.394" y1="28.138" y2="25.468" gradientUnits="userSpaceOnUse"><stop class="a8qa-cbgj"/><stop offset="1" class="b6mqj4mad"/></linearGradient><linearGradient id="iKd7FZf" x1="25.924" x2="24.712" y1="27.062" y2="23.913" gradientUnits="userSpaceOnUse"><stop offset=".228" class="lm86bn83x"/><stop offset="1" class="l1a_mnb5p"/></linearGradient><linearGradient id="iRwKvsc" x1="6.514" x2="6.514" y1="15.916" y2="25.32" gradientUnits="userSpaceOnUse"><stop offset=".395" class="zwcryw98i"/><stop offset="1" class="kytei3l2d"/></linearGradient><linearGradient id="iz1L2nt" x1="12.359" x2="12.359" y1="15.258" y2="27.291" gradientUnits="userSpaceOnUse"><stop offset=".395" class="g9s_xxbwl"/><stop offset=".758" class="ba7bvsb7n"/></linearGradient><filter id="iwqEwNe" width="22.598" height="20.153" x="2.342" y="8.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.356863 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7096"/></filter><filter id="i7duMlk" width="14.807" height="10.665" x="15.128" y="19.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.258824 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_7096"/></filter><filter id="ih6J9ze" width="13.325" height="6.947" x="16.434" y="21.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7096" stdDeviation=".75"/></filter><filter id="iikPLbb" width="3.813" height="11.405" x="4.608" y="14.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7096" stdDeviation=".5"/></filter><filter id="iULBnab" width="3.813" height="14.032" x="10.453" y="14.258" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7096" stdDeviation=".5"/></filter><filter id="iSzwjob" width="7.27" height="6.265" x="7.292" y="9.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_7096" stdDeviation=".75"/></filter></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji:index-pointing-at-the-viewer-medium-dark" {...props}></Icon>
<style>
:global(.a4vvbpb0h) {
  fill: var(--svg-color--835b4b, #835B4B);
  d: path("M24.304 22.067c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.664 5.994-3.815s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

:global(.a5t0acpmm) {
  fill: var(--svg-color--79544b, #79544B);
  d: path("M17.149 8.47c1.114 0 2.569.681 3.043 1.045l3.998.181V28.2l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.388-3.361-3.498v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.832 3.755-1.968c1.461-1.219 1.847-1.484 2.937-1.756c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

:global(.a8qa-cbgj) {
  stop-color: var(--svg-color--5f2f3f, #5F2F3F);
}

:global(.amlgsl62b) {
  stop-color: var(--svg-color--966f64, #966F64);
  stop-opacity: 0;
}

:global(.aoragubsy) {
  d: path("m14.695 26.764l.001-.003l.02.049l.034.056v.023c.324.74.867 1.484 2.172 1.484l7.267-.174V17.146l-9.68-.337v8.755c0 .622.103 1.012.185 1.2");
}

:global(.apn126baj) {
  stop-color: var(--svg-color--7b5454, #7B5454);
  stop-opacity: 0;
}

:global(.as0itkbft) {
  stop-color: var(--svg-color--613537, #613537);
}

:global(.axy2xmscy) {
  stop-color: var(--svg-color--77425b, #77425B);
  stop-opacity: 0;
}

:global(.b6mqj4mad) {
  stop-color: var(--svg-color--5f2f3f, #5F2F3F);
  stop-opacity: 0;
}

:global(.ba7bvsb7n) {
  stop-color: var(--svg-color--7e5b56, #7E5B56);
  stop-opacity: 0;
}

:global(.biwzbgssn) {
  width: 1.813px;
  height: 12.032px;
  x: 11.453px;
  y: 15.258px;
  rx: 0.906px;
}

:global(.c98-5wb0k) {
  stop-color: var(--svg-color--603e34, #603E34);
}

:global(.cbqhmti7m) {
  stop-color: var(--svg-color--79544b, #79544B);
  stop-opacity: 0;
}

:global(.cvydsjbla) {
  stop-color: var(--svg-color--7f5a4e, #7F5A4E);
  stop-opacity: 0;
}

:global(.djv207hfo) {
  stop-color: var(--svg-color--6a4037, #6A4037);
}

:global(.e02h3gx5p) {
  stop-color: var(--svg-color--603b2f, #603B2F);
}

:global(.e7a3kpxov) {
  stop-color: var(--svg-color--7a4270, #7A4270);
}

:global(.eca4lvb3u) {
  stop-color: var(--svg-color--7c5156, #7C5156);
  stop-opacity: 0;
}

:global(.eqw2qbtwv) {
  stop-color: var(--svg-color--7b5454, #7B5454);
}

:global(.f1wqexb4i) {
  stop-color: var(--svg-color--603e34, #603E34);
  stop-opacity: 0;
}

:global(.f8_uxtbzc) {
  stop-color: var(--svg-color--886b5e, #886B5E);
}

:global(.flh1x0chi) {
  stop-color: var(--svg-color--623938, #623938);
  stop-opacity: 0;
}

:global(.fr04q5b2f) {
  stop-color: var(--svg-color--694544, #694544);
  stop-opacity: 0;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g0z8bj9rv) {
  stop-color: var(--svg-color--623938, #623938);
}

:global(.g9s_xxbwl) {
  stop-color: var(--svg-color--7e5b56, #7E5B56);
}

:global(.h7--h-bqa) {
  stop-color: var(--svg-color--774d4d, #774D4D);
  stop-opacity: 0;
}

:global(.i3mt4q-ni) {
  stop-color: var(--svg-color--966f64, #966F64);
}

:global(.in55c-phu) {
  stop-color: var(--svg-color--805d4d, #805D4D);
}

:global(.jggu3dbyd) {
  stop-color: var(--svg-color--77524a, #77524A);
}

:global(.jho8eud8h) {
  d: path("M15.04 27.428a3.7 3.7 0 0 1-.344-.668c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468q-.029.047-.064.098a52 52 0 0 1-.026-1.731V13.925l5.996 2.684v8.46c0 .555.4 1.295.624 1.707c.067.125.118.22.138.27c-.04.098-.119.23-.23.382");
}

:global(.jq6js4_zj) {
  stop-color: var(--svg-color--79544b, #79544B);
}

:global(.kree96-eo) {
  width: 10.852px;
  height: 12.128px;
  x: 19.394px;
  y: 4.397px;
  rx: 5.426px;
}

:global(.kytei3l2d) {
  stop-color: var(--svg-color--83585d, #83585D);
  stop-opacity: 0;
}

:global(.l1a_mnb5p) {
  stop-color: var(--svg-color--a57e73, #A57E73);
  stop-opacity: 0;
}

:global(.ljh4ujb0d) {
  stop-color: var(--svg-color--784559, #784559);
}

:global(.lm86bn83x) {
  stop-color: var(--svg-color--a57e73, #A57E73);
}

:global(.mj_l97mnq) {
  stop-color: var(--svg-color--766057, #766057);
}

:global(.mqtzx-bbp) {
  stop-color: var(--svg-color--805b4f, #805B4F);
  stop-opacity: 0;
}

:global(.n0nwenbpt) {
  stop-color: var(--svg-color--7a544c, #7A544C);
}

:global(.oqyj8fbpq) {
  stop-color: var(--svg-color--764653, #764653);
  stop-opacity: 0;
}

:global(.orzf3j5tv) {
  stop-color: var(--svg-color--4f2a2c, #4F2A2C);
}

:global(.p1rx_0v1l) {
  stop-color: var(--svg-color--7e4d5e, #7E4D5E);
  stop-opacity: 0;
}

:global(.pnbzzm19n) {
  stop-color: var(--svg-color--5d3532, #5D3532);
}

:global(.q-hyakboh) {
  stop-color: var(--svg-color--784559, #784559);
  stop-opacity: 0;
}

:global(.q2wcuxbjh) {
  stop-color: var(--svg-color--684034, #684034);
  stop-opacity: 0;
}

:global(.q4u0j--_f) {
  stop-color: var(--svg-color--9f7d6e, #9F7D6E);
}

:global(.qh725-jas) {
  stop-color: var(--svg-color--9c796d, #9C796D);
}

:global(.qhj2xybpu) {
  stop-color: var(--svg-color--7c584c, #7C584C);
  stop-opacity: 0;
}

:global(.s1wtvyk-s) {
  d: path("M24.304 22.067c-.614.303-.954.605-1.484.605h-3.88c-1.386 0-3.81 1.166-3.81 3.907s2.361 3.815 3.81 3.815h4.398c4.586 0 5.738-2.664 5.994-3.815s.151-3.407-1.581-4.376c-1.257-.703-2.678-.515-3.446-.136");
}

:global(.s3aos1w9p) {
  stop-color: var(--svg-color--673d3e, #673D3E);
}

:global(.s8hogcyqx) {
  stop-color: var(--svg-color--713e53, #713E53);
  stop-opacity: 0;
}

:global(.so-u2ccpu) {
  stop-color: var(--svg-color--7d584c, #7D584C);
}

:global(.spq9hx54c) {
  stop-color: var(--svg-color--684034, #684034);
}

:global(.sqo2_1jyr) {
  stop-color: var(--svg-color--7a436d, #7A436D);
}

:global(.st_qpu9rb) {
  d: path("m8.602 25.784l.006.02a5 5 0 0 1-.096-1.027v-8.282l-6.156.65v6.648c-.04 1.11.734 3.498 3.361 3.498c1.673 0 2.562-.982 2.885-1.507");
}

:global(.szp84gm2l) {
  stop-color: var(--svg-color--77524a, #77524A);
  stop-opacity: 0;
}

:global(.ti-l9wb-i) {
  width: 1.813px;
  height: 9.405px;
  x: 5.608px;
  y: 15.916px;
  rx: 0.906px;
}

:global(.tm7g5gbnk) {
  stop-color: var(--svg-color--7c4d58, #7C4D58);
  stop-opacity: 0;
}

:global(.ttxd5bc4l) {
  fill: var(--svg-color--7f5b4d, #7F5B4D);
  d: path("M10.973 10.726c-1.005.17-1.878.949-2.18 1.393l2.937 1.787l1.332-2.968c-.757-.363-1.332-.34-2.09-.212");
}

:global(.u2yybui2i) {
  stop-color: var(--svg-color--5c3538, #5C3538);
  stop-opacity: 0;
}

:global(.uin3tjbzk) {
  stop-color: var(--svg-color--7a544c, #7A544C);
  stop-opacity: 0;
}

:global(.umkj4bzfu) {
  stop-color: var(--svg-color--643b3a, #643B3A);
}

:global(.uwho15b0m) {
  stop-color: var(--svg-color--7e4d5e, #7E4D5E);
}

:global(.v35k4mqxr) {
  d: path("M21.773 25.027H18.95a1.017 1.017 0 0 0 0 2.035h5.502c2.68 0 3.875-.778 3.803-2.496s-2.31-2.045-3.803-.249c-.662.796-2.221.667-2.68.71");
}

:global(.vbn2g9bgm) {
  stop-color: var(--svg-color--7b5b53, #7B5B53);
  stop-opacity: 0;
}

:global(.wdlwig3ok) {
  stop-color: var(--svg-color--7b5b53, #7B5B53);
}

:global(.wo80wzy-e) {
  stop-color: var(--svg-color--754d3d, #754D3D);
  stop-opacity: 0;
}

:global(.xfe801bjy) {
  d: path("M17.149 8.47c1.114 0 2.569.681 3.043 1.045l3.998.181V28.2l-7.268.174c-1.381 0-1.908-.833-2.226-1.613c-.227.485-1.181 1.492-2.846 1.492c-2.234 0-3.029-1.78-3.248-2.468c-.323.525-1.212 1.507-2.885 1.507c-2.627 0-3.401-2.388-3.361-3.498v-7.071c-.07-.646.085-2.162 1.272-3.059c1.484-1.12 2.15-.832 3.755-1.968c1.461-1.219 1.847-1.484 2.937-1.756c.977-.19 1.978.075 3.407-.265c1.224-.292 2.029-1.204 3.422-1.204");
}

:global(.y2k63wbop) {
  d: path("M21.404 24.959c0-3.101-.071-8.177-.152-10.327l7.01-2.18c.752 3.973 1.035 10.013 1.136 12.507z");
}

:global(.yicrqm3hs) {
  stop-color: var(--svg-color--a07a70, #A07A70);
}

:global(.yl2s6groo) {
  stop-color: var(--svg-color--684343, #684343);
  stop-opacity: 0;
}

:global(.ypxhk30rd) {
  stop-color: var(--svg-color--7c4d58, #7C4D58);
}

:global(.z79i4z1bd) {
  stop-color: var(--svg-color--9c796d, #9C796D);
  stop-opacity: 0;
}

:global(.z7y5oc_4f) {
  stop-color: var(--svg-color--805d4d, #805D4D);
  stop-opacity: 0;
}

:global(.zfckbmbwq) {
  stop-color: var(--svg-color--967064, #967064);
}

:global(.zrq_ottju) {
  stop-color: var(--svg-color--693945, #693945);
}

:global(.zwcryw98i) {
  stop-color: var(--svg-color--8a6964, #8A6964);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":227};
const content = `<defs><linearGradient x1="0%" y1="50%" x2="100%" y2="50%" id="ssvg-id-divshota"><stop offset=".54%" class="czcoitbqw"/><stop offset="100%" class="pem08lbpa"/></linearGradient><linearGradient x1="0%" y1="50%" x2="100%" y2="50%" id="ssvg-id-divshotb"><stop offset="22%" class="yneyhhkpw"/><stop offset="100%" class="ix0qi7pqb"/></linearGradient><linearGradient x1="0%" y1="50%" x2="99.999%" y2="50%" id="ssvg-id-divshotc"><stop offset="0%" class="yneyhhkpw"/><stop offset="100%" class="ix0qi7pqb"/></linearGradient><linearGradient x1="0%" y1="50%" x2="100%" y2="50%" id="ssvg-id-divshotd"><stop offset="0%" class="yneyhhkpw"/><stop offset="100%" class="ix0qi7pqb"/></linearGradient></defs><path fill="url(#ssvg-id-divshota)" class="xzabfhuvj"/><path fill="url(#ssvg-id-divshotb)" class="w1o0ykb0z"/><path fill="url(#ssvg-id-divshotc)" class="q-zo9f0mb"/><path fill="url(#ssvg-id-divshotd)" class="i03xq4bai"/><path fill="url(#ssvg-id-divshotd)" class="memm1rhck"/><path fill="url(#ssvg-id-divshotd)" class="w73n4hbnh"/><path fill="url(#ssvg-id-divshotd)" class="kcog_f7hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:divshot" {...props}></Icon>
<style>
:global(.czcoitbqw) {
  stop-color: var(--svg-color--f5ea14, #F5EA14);
}

:global(.i03xq4bai) {
  d: path("M100.693 191.147l-56.32-76.8H0l83.627 112.64H170.667l-25.6-35.84h-44.374z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

:global(.ix0qi7pqb) {
  stop-color: var(--svg-color--ff8e00, #FF8E00);
}

:global(.kcog_f7hy) {
  d: path("M170.667 0L256 114.347l-85.333 112.64l-25.6-35.84l56.326-76.8l-56.326-76.8L170.667 0z");
}

:global(.memm1rhck) {
  d: path("M201.387 114.347l-56.32-76.8h-44.374l56.32 76.8h44.374z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.pem08lbpa) {
  stop-color: var(--svg-color--f05b26, #F05B26);
}

:global(.q-zo9f0mb) {
  d: path("M145.067 191.147h-44.374l56.32-76.8h44.38l-56.326 76.8z");
}

:global(.w1o0ykb0z) {
  d: path("M128 0l27.307 39.253l-56.32 75.094l56.32 77.076l-28.16 35.564l-82.774-112.64L128 0z");
}

:global(.w73n4hbnh) {
  d: path("M83.627 0L0 114.347h44.373l56.32-76.8h44.374L170.667 0H83.627z");
}

:global(.xzabfhuvj) {
  d: path("M83.627 0L0 114.347l83.627 112.64H170.667L256 114.347L170.667 0H83.627zm73.386 114.347L128 153.6l-29.013-39.253L128 75.093l29.013 39.254z");
}

:global(.yneyhhkpw) {
  stop-color: var(--svg-color--ff0, #FF0);
}

</style>

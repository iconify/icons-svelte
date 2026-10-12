<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="xrm_jibas"/><path class="qjp3fzk3v"/><path class="hbgu0xbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:accessible-parking-sharp" {...props}></Icon>
<style>
:global(.hbgu0xbsk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 10v3h2.25l.75 2.25M14.4 11.5a2.6 2.6 0 1 0 3.1 4");
}

:global(.qjp3fzk3v) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 7.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xrm_jibas) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17V7h3a3 3 0 0 1 0 6h-3");
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="tudxz0p7t"/><circle class="jvrnx2_0k"/><path class="nzxsyubwa"/><path class="pit1cxi2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:face-detect-sharp" {...props}></Icon>
<style>
:global(.jvrnx2_0k) {
  cx: 12px;
  cy: 12px;
  r: 5.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nzxsyubwa) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 11h.01m3.49 0h.01");
}

:global(.pit1cxi2m) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 13.85L12 15.425l1.75-1.575");
}

:global(.tudxz0p7t) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7.5V3.25H7.5m9 0h4.25V7.5m0 9v4.25H16.5m-9 0H3.25V16.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

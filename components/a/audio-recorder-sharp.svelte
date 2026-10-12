<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="xrf4e9f4i"/><circle class="hyfgy206y"/><path class="jd6yzub2r"/><path class="k58stbbya"/><path class="fw6ra5b4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:audio-recorder-sharp" {...props}></Icon>
<style>
:global(.fw6ra5b4x) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 18.5h.01m2.99 0h.01m2.99 0h.01");
}

:global(.hyfgy206y) {
  cx: 16.5px;
  cy: 4.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jd6yzub2r) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.25L8.4 6.1M14 9.25l1.6-3.15M5.25 9.25h13.5v12H5.25z");
}

:global(.k58stbbya) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 11.75h8v4H8z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xrf4e9f4i) {
  cx: 7.5px;
  cy: 4.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="h__gfnb7z"/><circle class="m6jsykbla"/><path class="bq7hn8bxr"/><path class="jg3mm4bct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cash-payment" {...props}></Icon>
<style>
:global(.bq7hn8bxr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 10.5h.01m12.49 0h.01");
}

:global(.h__gfnb7z) {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 4.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.jg3mm4bct) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 19.25h13.5");
}

:global(.m6jsykbla) {
  cx: 12px;
  cy: 10.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

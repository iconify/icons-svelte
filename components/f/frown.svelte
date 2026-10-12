<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="pfz5sybjk"/><path class="dd_6j-l0z"/><path class="x6b1icb0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:frown" {...props}></Icon>
<style>
:global(.c6vt1lbds) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.dd_6j-l0z) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11h.01M15 11h.01");
}

:global(.pfz5sybjk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 8H10m4 0h2.5");
}

:global(.x6b1icb0p) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 16.75c1-.75 2.2-1.1 3.5-1.1s2.5.35 3.5 1.1");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

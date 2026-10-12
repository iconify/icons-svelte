<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="thm59gbch"/><rect class="r7so-bbux"/><path class="vwgqqw39o"/><path class="th7iub40n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:belt" {...props}></Icon>
<style>
:global(.r7so-bbux) {
  width: 6.5px;
  height: 10.5px;
  x: 7.5px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

:global(.th7iub40n) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 12h.01m2.49 0h.01");
}

:global(.thm59gbch) {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.vwgqqw39o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12h5.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

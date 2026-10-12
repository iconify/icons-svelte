<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rookl92lz"/><rect class="s1pcq53vz"/><path class="h4qapcb1m"/><circle class="phxq_-r2r"/><circle class="qp-tl-83e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:combine-harvester" {...props}></Icon>
<style>
:global(.h4qapcb1m) {
  d: path("M5.5 11H8m10-4l3.25-3.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.phxq_-r2r) {
  cx: 11px;
  cy: 18.25px;
  r: 3px;
}

:global(.qp-tl-83e) {
  cx: 19px;
  cy: 19.25px;
  r: 2px;
}

:global(.rookl92lz) {
  d: path("M8 12V3.75a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1V7H19a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1Zm2.25-7h1");
}

:global(.s1pcq53vz) {
  width: 2.75px;
  height: 6px;
  x: 2.75px;
  y: 9px;
  rx: 1px;
}

</style>

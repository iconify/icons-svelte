<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o2b98om6d"/><path class="n1egivbkx"/><circle class="ja6jjxzuf"/><path class="aj_x5rb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:access-card" {...props}></Icon>
<style>
:global(.aj_x5rb7x) {
  d: path("M8.75 17.25a3.25 3.25 0 0 1 6.5 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja6jjxzuf) {
  cx: 12px;
  cy: 9.75px;
  r: 2px;
}

:global(.n1egivbkx) {
  d: path("M10.25 5.25V3.5a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 .75.75v1.75");
}

:global(.o2b98om6d) {
  width: 12px;
  height: 16px;
  x: 6px;
  y: 5.25px;
  rx: 2.25px;
}

</style>

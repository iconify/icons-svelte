<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y50-ykb7m"/><rect class="lwou4gb-q"/><rect class="i4_8prb_y"/><path class="p6f5x8biq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:baby-bottle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4_8prb_y) {
  width: 6.5px;
  height: 10px;
  x: 8.75px;
  y: 11.25px;
  rx: 2.5px;
}

:global(.lwou4gb-q) {
  width: 8px;
  height: 2.5px;
  x: 8px;
  y: 6.5px;
  rx: 1.25px;
}

:global(.p6f5x8biq) {
  d: path("M8.75 14.5h2.5m-2.5 3.25h2.5");
}

:global(.y50-ykb7m) {
  d: path("M10.5 6.5V5a1.5 1.5 0 0 1 3 0v1.5Z");
}

</style>

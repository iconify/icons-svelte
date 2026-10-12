<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wukcdvqgk"/><path class="uvf6hsb-x"/><rect class="o3k2dhwru"/><path class="tl4nj2r-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boxes-stacked" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3k2dhwru) {
  width: 4px;
  height: 6.75px;
  x: 10px;
  y: 4.75px;
  rx: 0.5px;
}

:global(.tl4nj2r-y) {
  d: path("M14.5 17.25H18");
}

:global(.uvf6hsb-x) {
  d: path("M2.75 9.25h18.5");
}

:global(.wukcdvqgk) {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 4.75px;
  rx: 1.5px;
}

</style>

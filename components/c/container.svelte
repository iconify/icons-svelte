<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zmkaagbvv"/><rect class="sriu-7b3c"/><rect class="hu_ntz_gp"/><rect class="my527lywx"/><rect class="ttugeiezt"/><path class="v7fe81b1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:container" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hu_ntz_gp) {
  width: 4px;
  height: 4px;
  x: 17px;
  y: 12px;
  rx: 1px;
}

:global(.my527lywx) {
  width: 4px;
  height: 4px;
  x: 6.5px;
  y: 5px;
  rx: 1px;
}

:global(.sriu-7b3c) {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 12px;
  rx: 1px;
}

:global(.ttugeiezt) {
  width: 4px;
  height: 4px;
  x: 13.5px;
  y: 5px;
  rx: 1px;
}

:global(.v7fe81b1x) {
  d: path("M2.75 19.25h18.5");
}

:global(.zmkaagbvv) {
  width: 4px;
  height: 4px;
  x: 3px;
  y: 12px;
  rx: 1px;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wryae4b7k"/><rect class="rxb7_qbpa"/><rect class="ljadkk-9r"/><rect class="ply75h13t"/><path class="obuqlk-lg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dependency-graph" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ljadkk-9r) {
  width: 7px;
  height: 4.5px;
  x: 14.25px;
  y: 9.75px;
  rx: 1.5px;
}

:global(.obuqlk-lg) {
  d: path("m10 7.25l-2 2.5m6-2.5l2 2.5m-8 4.5l2 2.5m6-2.5l-2 2.5");
}

:global(.ply75h13t) {
  width: 7px;
  height: 4.5px;
  x: 8.5px;
  y: 16.75px;
  rx: 1.5px;
}

:global(.rxb7_qbpa) {
  width: 7px;
  height: 4.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 1.5px;
}

:global(.wryae4b7k) {
  width: 7px;
  height: 4.5px;
  x: 8.5px;
  y: 2.75px;
  rx: 1.5px;
}

</style>

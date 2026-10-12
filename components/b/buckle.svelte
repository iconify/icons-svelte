<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x1x79wb_q"/><path class="kbxo7mv5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:buckle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kbxo7mv5x) {
  d: path("M7.75 8.75h8.5a1 1 0 0 1 1 1v4.5a1 1 0 0 1-1 1h-8.5a1 1 0 0 1-1-1v-4.5a1 1 0 0 1 1-1m-3 3.25H14");
}

:global(.x1x79wb_q) {
  width: 17.5px;
  height: 13.5px;
  x: 3.25px;
  y: 5.25px;
  rx: 3px;
}

</style>

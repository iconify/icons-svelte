<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qjmjw-bcr"/><rect class="b-3rs1bba"/><path class="oeh_esbsg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:metric-down" {...props}></Icon>
<style>
:global(.b-3rs1bba) {
  width: 4px;
  height: 8px;
  x: 9px;
  y: 13.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oeh_esbsg) {
  d: path("M18 2.75V19.5m-3.25-3L18 19.75l3.25-3.25");
}

:global(.qjmjw-bcr) {
  width: 4px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  rx: 1px;
}

</style>

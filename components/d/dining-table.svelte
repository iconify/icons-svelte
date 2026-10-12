<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h4f5t265p"/><path class="q63jtt1th"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dining-table" {...props}></Icon>
<style>
:global(.h4f5t265p) {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q63jtt1th) {
  d: path("M5.5 9.25v12m13-12v12m-13-6h13");
}

</style>

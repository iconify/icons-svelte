<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ar3_hdb6g"/><path class="h-mw3y8lz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:potty-training" {...props}></Icon>
<style>
:global(.ar3_hdb6g) {
  width: 4.5px;
  height: 8.75px;
  x: 5px;
  y: 3px;
  rx: 1.75px;
}

:global(.h-mw3y8lz) {
  d: path("M4.75 11.75h14.5a1 1 0 0 1 1 1c0 3.6-2.9 6.25-6.5 6.25h-3.5c-3.6 0-6.5-2.65-6.5-6.25a1 1 0 0 1 1-1M8 21.25h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

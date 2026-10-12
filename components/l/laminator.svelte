<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="gie7himug"/><path class="pgyz0kbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:laminator" {...props}></Icon>
<style>
:global(.gie7himug) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 4.25px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pgyz0kbxu) {
  d: path("M6.25 10.25h11.5m-11 4h10.5v6a1 1 0 0 1-1 1h-8.5a1 1 0 0 1-1-1ZM10 19l2.5-2.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n31ubla9o"/><path class="j40-1f_nc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ice-floe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j40-1f_nc) {
  d: path("M2.5 13.5q2.375-1 4.75 0t4.75 0t4.75 0t4.75 0M5 18.5q2.375-1 4.75 0t4.75 0t4.75 0");
}

:global(.n31ubla9o) {
  d: path("M7.25 13.5L9 7.5L12.5 5l4.25 8.5M12.5 5l-.75 8.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggdwykbhe"/><path class="jp5ch4s9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-heart" {...props}></Icon>
<style>
:global(.ggdwykbhe) {
  d: path("M9 19S3.5 14 3.5 8.5a5.5 5.5 0 0 1 11 0C14.5 14 9 19 9 19");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jp5ch4s9o) {
  d: path("M7 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M18 21s-3.25-2-3.25-4.25c0-1 .75-1.75 1.75-1.75c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1 0 1.75.75 1.75 1.75C21.25 19 18 21 18 21");
}

</style>

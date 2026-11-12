<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="th_2vrbuv"/><path class="oorbizavx"/><path class="ghv12qbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-ellipsis-linear" {...props}></Icon>
<style>
:global(.ghv12qbis) {
  d: path("M8 12H8.009M11.991 12H12M15.991 12H16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oorbizavx) {
  d: path("M8 6L2 12L8 18");
}

:global(.th_2vrbuv) {
  d: path("M16 6L22 12L16 18");
}

</style>

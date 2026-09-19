<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fat9v2b0n"/><circle class="dh5nuddxy"/><path class="m09of8bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:downloader-for-gcam" {...props}></Icon>
<style>
:global(.dh5nuddxy) {
  cx: 14px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fat9v2b0n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.5 25.5h17v17h-17zm-3 17a17 17 0 0 1-17-17h17z");
}

:global(.m09of8bhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 5.5v9H27l7 8l7-8h-3.5v-9z");
}

</style>

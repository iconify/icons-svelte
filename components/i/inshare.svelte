<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kc64rtbmx"/><path class="ddk24b6bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:inshare" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ddk24b6bl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.51 22.137l5.93-3.253a4.025 4.025 0 1 0-1.204-2.273s-5.886 3.187-5.886 3.187");
}

:global(.kc64rtbmx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.398 29.816l-6.205-3.062a5.17 5.17 0 1 1 1.276-2.328s5.803 2.954 5.803 2.954a5.617 5.617 0 1 1-.874 2.436");
}

</style>

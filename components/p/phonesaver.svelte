<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uobm3abij"/><path class="s5yy5p9tc"/><path class="ddef0ebaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:phonesaver" {...props}></Icon>
<style>
:global(.ddef0ebaq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.37 31.56H36a5 5 0 0 1-5 5h-7m10.92-15.45L24 30.52");
}

:global(.s5yy5p9tc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.63 31.56H12a5 5 0 0 0 5 5h7m0-6.04V5.5M13.08 21.11L24 30.52m5.83-15.13H39l3.41 16.17A10.94 10.94 0 0 1 31.43 42.5H24");
}

:global(.uobm3abij) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.17 15.39H9L5.63 31.56A10.94 10.94 0 0 0 16.57 42.5H24");
}

</style>

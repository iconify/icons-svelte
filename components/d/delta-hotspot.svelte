<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ksrzkulwb"/><circle class="laix5fbpb"/><path class="ybfhly8cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:delta-hotspot" {...props}></Icon>
<style>
:global(.ksrzkulwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 5.5h10v10h-10zm0 27h10v10h-10z");
}

:global(.laix5fbpb) {
  cx: 10.5px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ybfhly8cb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 32.5L24 24l8.5-8.5M24 24h-8.5");
}

</style>

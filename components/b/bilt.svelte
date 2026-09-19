<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k2_f04bfz"/><circle class="db5arjb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bilt" {...props}></Icon>
<style>
:global(.db5arjb0l) {
  cx: 24px;
  cy: 24px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k2_f04bfz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24L34.75 42.62h-21.5L2.5 24L13.25 5.38h21.5z");
}

</style>

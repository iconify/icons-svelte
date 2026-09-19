<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m7_jq0g_l"/><path class="cfyreebij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:laboralkutxa" {...props}></Icon>
<style>
:global(.cfyreebij) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.51 43.5H24V25.72m0 12.99h3.96");
}

:global(.m7_jq0g_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a10.61 10.61 0 1 0 10.61 10.61");
}

</style>

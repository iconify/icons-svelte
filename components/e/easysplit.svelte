<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rt79d9moi"/><path class="r6v5m5j7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:easysplit" {...props}></Icon>
<style>
:global(.r6v5m5j7k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 20l-8.836 15.304a10.39 10.39 0 0 1-9 5.196h-14.5L22 20z");
}

:global(.rt79d9moi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.836 7.5L26 28H5.5l8.836-15.304a10.39 10.39 0 0 1 9-5.196z");
}

</style>

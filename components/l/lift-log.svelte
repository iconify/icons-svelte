<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wglk0eb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lift-log" {...props}></Icon>
<style>
:global(.wglk0eb7y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.987 7.08L40.63 40.724M15.98 5.755L5.81 15.925M22.153 5.5l-16.6 16.6m36.637 9.974l-10.17 10.17M42.446 25.9l-16.6 16.6");
}

</style>

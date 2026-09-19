<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0rbx7bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cimb-th" {...props}></Icon>
<style>
:global(.j0rbx7bat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.604 24L4.5 8.267h26.942L43.5 24zL4.5 39.733h26.942L43.5 24");
}

</style>

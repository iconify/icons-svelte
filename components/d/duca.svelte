<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gp648yq7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:duca" {...props}></Icon>
<style>
:global(.gp648yq7k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.167 5.5v24.667H42.5V17.833zm0 0H5.5m24.667 3.083H5.5m24.667 3.084H5.5m24.667 3.083H5.5m24.667 3.083H5.5m24.667 12.334H5.5m33.917 3.083H5.5m30.833 3.083H5.5m27.75 3.084H5.5M30.167 42.5H5.5");
}

</style>

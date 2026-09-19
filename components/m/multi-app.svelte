<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r3hxiol4p"/><path class="knw842h5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:multi-app" {...props}></Icon>
<style>
:global(.knw842h5k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.69 40.125v-21.5l18.62-10.75v10.75");
}

:global(.r3hxiol4p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5V24l18.62-10.75v21.5zL5.38 34.75v-21.5L24 2.5v10.75");
}

</style>

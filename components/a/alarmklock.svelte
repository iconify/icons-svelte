<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vk3156f6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alarmklock" {...props}></Icon>
<style>
:global(.vk3156f6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5m2 5.86a13.69 13.69 0 1 0 13.64 13.69A13.69 13.69 0 0 0 26 8.36m-.05 13.69V10.72");
}

</style>

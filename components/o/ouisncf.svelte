<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vcrzmx-8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ouisncf" {...props}></Icon>
<style>
:global(.vcrzmx-8b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.25 35.37H32.6a14.25 14.25 0 1 0-17.2 0H5.76a21.5 21.5 0 1 1 36.49 0");
}

</style>

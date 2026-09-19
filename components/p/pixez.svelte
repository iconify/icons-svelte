<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ey53vhpae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pixez" {...props}></Icon>
<style>
:global(.ey53vhpae) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.55 6.84h9.4v34.32h-9.4zm14.45 0a12.51 12.51 0 0 1 0 25");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bn8s3he_x"/><path class="ys0e38nmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rabble-cachebook" {...props}></Icon>
<style>
:global(.bn8s3he_x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.5 5.5h17c2.216 0 4 1.784 4 4v17c0 8.864-7.136 16-16 16h-17c-2.216 0-4-1.784-4-4v-17c0-8.864 7.136-16 16-16");
}

:global(.ys0e38nmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 26v10h10m4-24h10v10");
}

</style>

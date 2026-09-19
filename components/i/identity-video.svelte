<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="maxbavjlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:identity-video" {...props}></Icon>
<style>
:global(.maxbavjlq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.372 42.276L42.5 9.086l-3.587-3.362L11.372 35.09V20.736H5.5v21.54zM5.5 12.299h5.872v4.632H5.5z");
}

</style>

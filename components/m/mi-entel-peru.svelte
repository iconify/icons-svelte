<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yodp4f73w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mi-entel-peru" {...props}></Icon>
<style>
:global(.yodp4f73w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.985 23.497H4.5c0-20.416 23.485-20.416 23.485 0m0 12.252C17.771 43.925 4.5 39.837 4.5 23.497M35.84 8.163c10.214 6.126 10.214 24.504 0 30.63");
}

</style>

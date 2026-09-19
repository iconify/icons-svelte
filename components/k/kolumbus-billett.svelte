<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="in_pr1bit"/><path class="c33zsnbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kolumbus-billett" {...props}></Icon>
<style>
:global(.c33zsnbjf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.371 24l-15.613-9.128V4.5l24.484 14.314");
}

:global(.in_pr1bit) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.242 18.814L11.758 33.128V43.5l24.484-14.314z");
}

</style>

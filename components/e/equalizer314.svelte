<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="chseogods"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:equalizer314" {...props}></Icon>
<style>
:global(.chseogods) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.383 24.23h8.514v18.162H5.383zM19.743 5.5h8.514v36.892h-8.514zm14.361 12.027h8.514V42.5h-8.514z");
}

</style>

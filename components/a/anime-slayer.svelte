<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z4kab2bxk"/><path class="e0a7q4b_v"/><path class="gnadfqc-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:anime-slayer" {...props}></Icon>
<style>
:global(.e0a7q4b_v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.65 43.5c-3.8-6.47-10.11-28.766-10.981-36.026");
}

:global(.gnadfqc-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.027 30.936c8.411-.151 23.94-3.63 31.946-7.592");
}

:global(.z4kab2bxk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.489 41.541C12.07 33.858 20.805 13.639 26.386 4.5");
}

</style>

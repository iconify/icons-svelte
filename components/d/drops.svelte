<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0ag7s5np"/><path class="hxq7w6ncb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:drops" {...props}></Icon>
<style>
:global(.hxq7w6ncb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.295 22.033a7.584 7.584 0 1 1-10.689 0l5.345-5.17Z");
}

:global(.z0ag7s5np) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.444 15.593a16.311 16.311 0 1 1-22.987 0L23.95 4.475Z");
}

</style>

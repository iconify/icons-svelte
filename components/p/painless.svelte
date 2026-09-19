<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pxu8s8adf"/><path class="odwnme9-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:painless" {...props}></Icon>
<style>
:global(.odwnme9-y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.389 16.5C24.312 18.332 23 21.012 23 24s1.311 5.668 3.389 7.5H36c4.155 0 7.5-3.345 7.5-7.5s-3.345-7.5-7.5-7.5zM8.5 24H21m-10.436-3.5h10.958m-10.958 7h10.958");
}

:global(.pxu8s8adf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.632 31.5H12c-4.155 0-7.5-3.345-7.5-7.5s3.345-7.5 7.5-7.5h11.632");
}

</style>

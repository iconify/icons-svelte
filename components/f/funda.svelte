<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jv00kgq7p"/><path class="x2-rmpxdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:funda" {...props}></Icon>
<style>
:global(.jv00kgq7p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.192 32.858v-13.82a2.93 2.93 0 0 1 2.93-2.93c1.444 0 2.344.427 2.962 1.227m-8.376 4.425h5.863");
}

:global(.x2-rmpxdo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 39.652h19.072a14.914 14.914 0 0 0 14.388-10.99L43.5 8.348H24.428a14.914 14.914 0 0 0-14.388 10.99z");
}

</style>

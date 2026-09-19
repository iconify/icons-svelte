<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="bnx04z7uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:forcelte" {...props}></Icon>
<style>
:global(.bnx04z7uq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.927 30.5l-.001-13l-6.976 8.732h8.612m11.488-4.426a4.306 4.306 0 0 0-4.306-4.306h0a4.306 4.306 0 0 0-4.306 4.306v4.388a4.306 4.306 0 0 0 4.306 4.306h0a4.306 4.306 0 0 0 4.306-4.306h-4.306");
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>

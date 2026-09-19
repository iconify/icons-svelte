<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihvqhub0d"/><path class="gbw11kz7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hivedisk" {...props}></Icon>
<style>
:global(.gbw11kz7e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.38 29.375L24 18.625l18.62 10.75");
}

:global(.ihvqhub0d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5z");
}

</style>

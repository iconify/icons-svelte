<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sv-s-xb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:edrawmax" {...props}></Icon>
<style>
:global(.sv-s-xb2o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5H24c10.217 0 18.5 8.283 18.5 18.5S34.217 42.5 24 42.5H5.5M24 24H5.5");
}

</style>

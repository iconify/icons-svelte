<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f45gmdb1f"/><path class="iu24r3r3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:banque-saudi-fransi" {...props}></Icon>
<style>
:global(.f45gmdb1f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75v-21.5zm0 0v43");
}

:global(.iu24r3r3i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.379 13.248A37.24 37.24 0 0 1 24 45.5a37.24 37.24 0 0 1 18.621-32.252");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qj0ktchqm"/><path class="q25en_b4w"/><path class="k1-d_-5kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:m64plus-fz" {...props}></Icon>
<style>
:global(.k1-d_-5kn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.862 28.855l4.58-3.016l-3.672 8.53l4.643-3.12M24.08 43.002V26.53");
}

:global(.q25en_b4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.569 16.266V32.74L24.08 43.002L7.591 32.74V16.266");
}

:global(.qj0ktchqm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.08 26.53L7.591 16.266L24.08 6.002l16.489 10.264z");
}

</style>

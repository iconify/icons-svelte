<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jwt0polzr"/><path class="q42k_o-op"/><path class="nakn0cb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:animezone" {...props}></Icon>
<style>
:global(.jwt0polzr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.11L4.5 40.89h39z");
}

:global(.nakn0cb_b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.09 24.59H19.45l.96 4.21h5.94l-6.98 12.09");
}

:global(.q42k_o-op) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.55 24.59L24 16.71L12.47 36.68h9.33m12.4-11.89l-6.86 11.89h8.19l-4.1-7.1");
}

</style>

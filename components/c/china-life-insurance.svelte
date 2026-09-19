<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ynv8_vb_k"/><circle class="rmwop1a6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:china-life-insurance" {...props}></Icon>
<style>
:global(.rmwop1a6h) {
  cx: 35.177px;
  cy: 12.608px;
  r: 8.108px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ynv8_vb_k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.45 26.559A18.919 18.919 0 1 1 21.327 5.804");
}

</style>

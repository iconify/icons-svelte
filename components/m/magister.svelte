<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wac2npwnj"/><circle class="g2qvqqb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:magister" {...props}></Icon>
<style>
:global(.g2qvqqb-w) {
  cx: 40.328px;
  cy: 35.225px;
  r: 3.172px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wac2npwnj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 38.365l5.57-28.762l8.827 19.967l8.826-19.923l5.571 28.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hjyf5uaje"/><path class="cyc06j_hv"/><circle class="yxrav5bru"/><circle class="tnriovlnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:like-a-dino" {...props}></Icon>
<style>
:global(.cyc06j_hv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.752 29.939s6.322 6.235 13.053 1.163");
}

:global(.hjyf5uaje) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.196 18.172c.459-10.217 19.877-16.964 27.151 2.157c6.566 18.864-16.426 22.457-29.754 17.41C2.71 35.079.033 21.554 15.196 18.17");
}

:global(.tnriovlnn) {
  cx: 28.71px;
  cy: 17.604px;
  r: 0.75px;
  fill: currentColor;
}

:global(.yxrav5bru) {
  cx: 20.639px;
  cy: 16.388px;
  r: 0.75px;
  fill: currentColor;
}

</style>

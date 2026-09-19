<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="f4cwobb6e"/><circle class="ypi354_ok"/><circle class="ga4bzcf5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:my-optimum" {...props}></Icon>
<style>
:global(.f4cwobb6e) {
  cx: 17.639px;
  cy: 24px;
  r: 4.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ga4bzcf5q) {
  cx: 37.478px;
  cy: 31.117px;
  r: 6.022px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ypi354_ok) {
  cx: 17.639px;
  cy: 24px;
  r: 13.139px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

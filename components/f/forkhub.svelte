<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="jtdoh9bdf"/><circle class="j7ymcybsg"/><circle class="lyuiivbah"/><path class="jf-j82b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:forkhub" {...props}></Icon>
<style>
:global(.j7ymcybsg) {
  cx: 16.1px;
  cy: 9.08px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jf-j82b1i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.1 34.34V13.66m0 19.01c0-5.4 5-8.67 11.22-8.67");
}

:global(.jtdoh9bdf) {
  cx: 16.1px;
  cy: 38.92px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lyuiivbah) {
  cx: 31.9px;
  cy: 24px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

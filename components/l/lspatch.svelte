<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="jjluhcb9b"/><circle class="wt__1abch"/><circle class="h-ys6zb5i"/><circle class="rmc36ebie"/><path class="zyp__ldxg"/><path class="xcg2crgne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lspatch" {...props}></Icon>
<style>
:global(.h-ys6zb5i) {
  cx: 20.247px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jjluhcb9b) {
  cx: 24px;
  cy: 20.247px;
  r: 0.75px;
  fill: currentColor;
}

:global(.rmc36ebie) {
  cx: 24px;
  cy: 27.753px;
  r: 0.75px;
  fill: currentColor;
}

:global(.wt__1abch) {
  cx: 27.753px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.xcg2crgne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.65 23.995l7.274 7.274a1.955 1.955 0 0 1 0 2.765l-7.892 7.891a1.955 1.955 0 0 1-2.765 0l-7.274-7.274M13.347 24.005L6.074 16.73a1.955 1.955 0 0 1 0-2.765l7.891-7.891a1.955 1.955 0 0 1 2.765 0l7.274 7.273");
}

:global(.zyp__ldxg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.962 41.927l-7.89-7.89a1.955 1.955 0 0 1 0-2.764l25.2-25.2a1.955 1.955 0 0 1 2.766 0l7.89 7.89a1.955 1.955 0 0 1 0 2.764l-25.2 25.2a1.955 1.955 0 0 1-2.766 0");
}

</style>

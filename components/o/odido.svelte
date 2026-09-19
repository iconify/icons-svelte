<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="n3u7j36vn"/><path class="y87hdmqfu"/><circle class="k4g0qzb0w"/><path class="dk5k-ibhv"/><path class="fbn33obsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:odido" {...props}></Icon>
<style>
:global(.dk5k-ibhv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.034 18.017a5.983 5.983 0 1 0 0 11.966z");
}

:global(.fbn33obsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.009 18.017h6.043v11.966h-6.043z");
}

:global(.k4g0qzb0w) {
  cx: 39.017px;
  cy: 24px;
  r: 5.983px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.n3u7j36vn) {
  cx: 8.983px;
  cy: 24px;
  r: 5.983px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y87hdmqfu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.966 18.017a5.983 5.983 0 1 1 0 11.966z");
}

</style>

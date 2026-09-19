<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="klvlxwbvc"/><circle class="wtdkvu9ae"/><path class="tthskmbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:compass" {...props}></Icon>
<style>
:global(.klvlxwbvc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 1 45.5 24A21.51 21.51 0 0 1 24 45.5m12.45-34.08l-12.3 8.96m12.3-8.96l-8.96 12.31");
}

:global(.tthskmbvv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.54 36.34l12.3-8.96m-12.3 8.96l8.96-12.3");
}

:global(.wtdkvu9ae) {
  cx: 24px;
  cy: 23.88px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

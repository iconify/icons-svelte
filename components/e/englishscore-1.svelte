<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dh5nuddxy"/><circle class="khsgttbqg"/><circle class="elsmppbpr"/><circle class="oxml-db7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:englishscore-1" {...props}></Icon>
<style>
:global(.dh5nuddxy) {
  cx: 14px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.elsmppbpr) {
  cx: 14px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.khsgttbqg) {
  cx: 34px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oxml-db7v) {
  cx: 34px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

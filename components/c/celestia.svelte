<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bsn60jbjf"/><circle class="ko4415bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:celestia" {...props}></Icon>
<style>
:global(.bsn60jbjf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.52 10.964a15.05 15.05 0 1 0 0 26.066l9.42.206a21.499 21.499 0 1 1 0-26.472Z");
}

:global(.ko4415bth) {
  cx: 23.939px;
  cy: 23.943px;
  r: 10.749px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

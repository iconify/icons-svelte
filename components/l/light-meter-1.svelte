<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="hlyv62rlk"/><path class="rglnnob8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:light-meter-1" {...props}></Icon>
<style>
:global(.hlyv62rlk) {
  cx: 24px;
  cy: 17.59px;
  r: 9.87px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rglnnob8e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.96 30.71C42.96 13.54 32.61 4.29 24 4.29S5.04 13.54 5.04 30.71c0 0-.13 8.25 1.75 13h34.42c1.88-4.3 1.75-13 1.75-13");
}

</style>

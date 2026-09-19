<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lpp96yb1v"/><circle class="bx624wbmq"/><path class="yckq7tdls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:finale" {...props}></Icon>
<style>
:global(.bx624wbmq) {
  cx: 18.868px;
  cy: 34.776px;
  r: 8.724px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lpp96yb1v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.592 34.776V4.5");
}

:global(.yckq7tdls) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.855 4.5H27.592m10.263 10.263H27.592");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="en2kjqufx"/><circle class="db5arjb0l"/><circle class="r0t0p9p8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myinsta" {...props}></Icon>
<style>
:global(.db5arjb0l) {
  cx: 24px;
  cy: 24px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.en2kjqufx) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9px;
  ry: 9px;
}

:global(.r0t0p9p8v) {
  cx: 12.932px;
  cy: 12.932px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

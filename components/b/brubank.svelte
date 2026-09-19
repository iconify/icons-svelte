<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ye75ejbyp"/><circle class="theuptidz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:brubank" {...props}></Icon>
<style>
:global(.theuptidz) {
  cx: 24px;
  cy: 28px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ye75ejbyp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.5A15.5 15.5 0 1 1 8.5 28V4.5");
}

</style>

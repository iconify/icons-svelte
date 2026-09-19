<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sv38ogbzn"/><circle class="u8kdebxej"/><path class="qj554fbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cureskin" {...props}></Icon>
<style>
:global(.qj554fbra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 30.5a6.5 6.5 0 1 1 0-13H37a6.5 6.5 0 1 1 0 13z");
}

:global(.sv38ogbzn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 30.5a6.5 6.5 0 1 1 0-13z");
}

:global(.u8kdebxej) {
  cx: 17.5px;
  cy: 24px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

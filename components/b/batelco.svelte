<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b-ed7sokm"/><circle class="beqsa12ge"/><circle class="oynlhd-_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:batelco" {...props}></Icon>
<style>
:global(.b-ed7sokm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 5.5zA9.25 9.25 0 0 1 24 14.75v18.5a9.25 9.25 0 0 1-18.5 0v-18.5a9.25 9.25 0 0 1 9.25-9.25");
}

:global(.beqsa12ge) {
  cx: 33.25px;
  cy: 14.75px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oynlhd-_h) {
  cx: 33.25px;
  cy: 33.25px;
  r: 9.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

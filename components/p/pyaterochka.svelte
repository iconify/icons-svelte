<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ajgiri0it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pyaterochka" {...props}></Icon>
<style>
:global(.ajgiri0it) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.667 30.973a8.142 8.142 0 0 0 15.685-3.057a8.14 8.14 0 0 0-15.487-3.507M36.45 6.471l-7.727.208a10.41 10.41 0 0 0-9.673 7.354l-.263.855l7.746-.205a10.41 10.41 0 0 0 9.772-7.678zM15.865 24.409l2.922-9.521");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

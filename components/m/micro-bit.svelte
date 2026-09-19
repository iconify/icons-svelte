<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r1ni5gbfy"/><circle class="iw5aw-blo"/><circle class="jsm3a-v1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:micro-bit" {...props}></Icon>
<style>
:global(.iw5aw-blo) {
  cx: 14.5px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jsm3a-v1b) {
  cx: 33.5px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r1ni5gbfy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 15h21a9 9 0 0 1 9 9h0a9 9 0 0 1-9 9h-21a9 9 0 0 1-9-9h0a9 9 0 0 1 9-9");
}

</style>

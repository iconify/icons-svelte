<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="r8t3p3bxd"/><rect class="toi9nfsrh"/><path class="dsa6zjzhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nds4droid" {...props}></Icon>
<style>
:global(.dsa6zjzhz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29l4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.r8t3p3bxd) {
  width: 16.4px;
  height: 12.2px;
  x: 15.8px;
  y: 10.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.toi9nfsrh) {
  width: 16.4px;
  height: 12.2px;
  x: 15.8px;
  y: 25.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>

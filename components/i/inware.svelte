<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="t1mfal-np"/><path class="pe3knyllu"/><rect class="wss7nob4e"/><path class="wuebimbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:inware" {...props}></Icon>
<style>
:global(.pe3knyllu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 29h-6m6-10h-6m-25 10h-6m6-10h-6");
}

:global(.t1mfal-np) {
  cx: 24px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wss7nob4e) {
  width: 25px;
  height: 25px;
  x: 11.5px;
  y: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
}

:global(.wuebimbem) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19 42.5v-6m10 6v-6m-10-25v-6m10 6v-6");
}

</style>

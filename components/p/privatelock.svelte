<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vb_uuxzdb"/><rect class="bvsztp53f"/><path class="zje1zosoz"/><circle class="n5anpub0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:privatelock" {...props}></Icon>
<style>
:global(.bvsztp53f) {
  width: 17.39px;
  height: 13.4px;
  x: 15.31px;
  y: 19.26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.05px;
}

:global(.n5anpub0v) {
  cx: 24px;
  cy: 25.96px;
  r: 2.23px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vb_uuxzdb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.2 4.86L6.69 11.25V27C6.69 35.44 24 43.5 24 43.5S41.31 35.44 41.31 27V11.25L25.8 4.86a4.68 4.68 0 0 0-3.6 0");
}

:global(.zje1zosoz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.25 19.26v-2.41a5.75 5.75 0 0 1 11.5 0v2.41");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ay5p0cc-h"/><rect class="sb-99x-xo"/><rect class="nu7hn2sdy"/><rect class="m0r0tgp0x"/><rect class="h229szbbf"/><rect class="mnps2f2gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:magic-widgets" {...props}></Icon>
<style>
:global(.ay5p0cc-h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 22h-33a2 2 0 0 1-2-2V7.5a2 2 0 0 1 2-2h33a2 2 0 0 1 2 2V20a2 2 0 0 1-2 2");
}

:global(.h229szbbf) {
  width: 6.452px;
  height: 6.452px;
  x: 36.048px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.m0r0tgp0x) {
  width: 6.452px;
  height: 6.452px;
  x: 26px;
  y: 36.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.mnps2f2gm) {
  width: 6.452px;
  height: 6.452px;
  x: 36.048px;
  y: 36.048px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.nu7hn2sdy) {
  width: 6.452px;
  height: 6.452px;
  x: 26px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.sb-99x-xo) {
  width: 16.5px;
  height: 16.5px;
  x: 5.5px;
  y: 26px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

</style>

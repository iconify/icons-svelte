<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="g303qebei"/><circle class="dfh2fbp3r"/><path class="aw09g8-gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boomplay" {...props}></Icon>
<style>
:global(.aw09g8-gk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26 12l-10.7-1.2m9.8 16.9l-13.3-1.5m17.6-3.6c5.5 0 10 4.5 10 10s-4.5 10-10 10H12.2c-2.1 0-3.6-1.9-3.2-4l7-32c.1-.6.7-1 1.3-1h11.8c4.7 0 8.4 3.8 8.4 8.5c0 4.5-3.5 8.3-8.1 8.5");
}

:global(.dfh2fbp3r) {
  cx: 24.8px;
  cy: 31.8px;
  r: 4.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.g303qebei) {
  cx: 25.8px;
  cy: 15.3px;
  r: 3.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

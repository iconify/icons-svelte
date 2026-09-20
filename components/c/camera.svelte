<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q74ya9che"/><path class="zyxhuxbbz"/><circle class="g2ql4oemh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:camera" {...props}></Icon>
<style>
:global(.g2ql4oemh) {
  cx: 38.5px;
  cy: 17.02px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q74ya9che) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.92a8.5 8.5 0 1 1-8.5 8.5a8.5 8.5 0 0 1 8.5-8.5");
}

:global(.zyxhuxbbz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 12.02h-8l-2.594-4h-9.812l-2.594 4h-8a4 4 0 0 0-4 4v18.8a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4v-18.8a4 4 0 0 0-4-4");
}

</style>

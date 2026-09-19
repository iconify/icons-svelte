<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d3ny2ac9a"/><circle class="mukj8eb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-face-open-mouth" {...props}></Icon>
<style>
:global(.d3ny2ac9a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.194 16.359v2.413m-12.307-2.413v2.413M24.04 42.5c10.215 0 18.46-8.285 18.46-18.54c0-10.215-8.245-18.46-18.46-18.46C13.785 5.5 5.5 13.745 5.5 23.96c0 10.255 8.285 18.54 18.54 18.54");
}

:global(.mukj8eb7w) {
  cx: 24.041px;
  cy: 31.038px;
  r: 4.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mc30fubfn"/><path class="ww19kz7zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nosurfreddit" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mc30fubfn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 15.1a8.85 8.85 0 1 0 15 9.41a8.85 8.85 0 0 1 15 9.41A17.69 17.69 0 1 1 9 15.1");
}

:global(.ww19kz7zb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.19 16.09a4.36 4.36 0 1 0-8.08 3.3a4.36 4.36 0 1 1-8.11 3.3a8.73 8.73 0 1 1 16.16-6.6");
}

</style>

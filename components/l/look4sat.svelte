<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ahf75yaif"/><circle class="jujcs3brl"/><path class="ow3qb4bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:look4sat" {...props}></Icon>
<style>
:global(.ahf75yaif) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.47 19.28A23.42 23.42 0 0 1 28.7 7.8m.46-.21l-23.43 11m34.74.69L31 40.85");
}

:global(.jujcs3brl) {
  cx: 34.54px;
  cy: 13.69px;
  r: 8.18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ow3qb4bpn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31 21.22L14 42.27M26.2 14l-10.36 7.07");
}

</style>

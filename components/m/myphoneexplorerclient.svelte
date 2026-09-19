<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mhoj3acuf"/><path class="j1lngdvbr"/><path class="t4nnyrb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myphoneexplorerclient" {...props}></Icon>
<style>
:global(.j1lngdvbr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.56 42.9l-7.12-7.5l7.12-7.51m-18.32-.35c-1-11.61 2.44-15.9 18.33-14.93");
}

:global(.mhoj3acuf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.76 20.46c1 11.61-2.44 15.9-18.33 14.93");
}

:global(.t4nnyrb1x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.47 5.13l7.12 7.5l-7.12 7.51");
}

</style>

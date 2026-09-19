<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g60jk2bmy"/><path class="a93d34boh"/><path class="ki_hnyslh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:online-bibliotheek" {...props}></Icon>
<style>
:global(.a93d34boh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.27 23.58h.84a1 1 0 0 1 1 1v6.92a1 1 0 0 1-1 1h-.84a4.43 4.43 0 0 1-4.44-4.5v0a4.43 4.43 0 0 1 4.44-4.42m15.46-.3a7.73 7.73 0 0 0-15.46 0m0 .3v8.87");
}

:global(.g60jk2bmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.35 5.6c6.12 0 10.15 3.21 10.15 10.81s-4.08 26-17.8 26S4.5 29.2 4.5 22.87C4.5 13.13 23.62 5.6 33.35 5.6");
}

:global(.ki_hnyslh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.74 32.16h-.84a1 1 0 0 1-1-1v-6.92a1 1 0 0 1 1-1h.84a4.43 4.43 0 0 1 4.43 4.43h0a4.43 4.43 0 0 1-4.43 4.49m-.01-8.88v8.87");
}

</style>

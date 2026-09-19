<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rglytubot"/><path class="bqpdo5bhb"/><circle class="cpk0fnbgt"/><path class="l5pthe99e"/><path class="zo7trbwvq"/><path class="mly8g8bgp"/><path class="aj8riabne"/><path class="guxd_61ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:owlgram" {...props}></Icon>
<style>
:global(.aj8riabne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.235 11.8a6.793 6.793 0 0 0-.173 9.613a6.927 6.927 0 0 0 9.72-.211");
}

:global(.bqpdo5bhb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.508 19.928a3.174 3.174 0 0 0 4.477.069a3.11 3.11 0 0 0-.05-4.424");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.guxd_61ws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.066 15.573a3.11 3.11 0 0 0-.05 4.424a3.174 3.174 0 0 0 4.476-.07m-1.987 3.142h5.173m6.644 0h5.173");
}

:global(.l5pthe99e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.33 23.069v14.86H11.67v-14.86m9.189 7.793l-9.193 4.849");
}

:global(.mly8g8bgp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.557 10.148L24 26.34l16.443-16.192");
}

:global(.rglytubot) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.334 35.711l-9.193-4.85m2.077-9.659a6.927 6.927 0 0 0 9.72.211a6.793 6.793 0 0 0-.174-9.612");
}

:global(.zo7trbwvq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.33 23.069c-3.498 3.648-7.13 8.363-12.41 8.363s-8.752-4.715-12.25-8.363");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gco1bibwb"/><circle class="ckn4tobva"/><path class="z3h1qbb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:db-bahnhof-live" {...props}></Icon>
<style>
:global(.ckn4tobva) {
  cx: 24px;
  cy: 19.988px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gco1bibwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 26.25h10v11m-5-11v11m-34 0v-11h10m-5 11v-11m5 11v-26.5h19v26.5");
}

:global(.z3h1qbb3h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.094 18.877L24 21.107l2.906-2.23");
}

</style>

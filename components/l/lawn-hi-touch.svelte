<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eqkpnibsz"/><circle class="p5uql8byd"/><path class="s94ofobxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lawn-hi-touch" {...props}></Icon>
<style>
:global(.eqkpnibsz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.25 8.5v8c0 1.662 1.338 3 3 3h5.5c1.662 0 3-1.338 3-3v-8c0-1.662 1.338-3 3-3H38c1.662 0 3 1.338 3 3v31c0 1.662-1.338 3-3 3h-5.25c-1.662 0-3-1.338-3-3v-8c0-1.662-1.338-3-3-3h-5.5c-1.662 0-3 1.338-3 3v8c0 1.662-1.338 3-3 3H10c-1.662 0-3-1.338-3-3v-31c0-1.662 1.338-3 3-3h5.25c1.662 0 3 1.338 3 3");
}

:global(.p5uql8byd) {
  cx: 35.375px;
  cy: 15.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s94ofobxb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.375 22.5v20");
}

</style>

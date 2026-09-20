<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cdpqd_bya"/><path class="d_4gau5sg"/><path class="q2yv-wrex"/><path class="prgvtl7pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:reolink" {...props}></Icon>
<style>
:global(.cdpqd_bya) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.364 24.079v7.4h7.4");
}

:global(.d_4gau5sg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.364 24.079a7.4 7.4 0 0 1 7.4-7.4a7.4 7.4 0 0 1 7.4 7.4a7.4 7.4 0 0 1-7.4 7.4");
}

:global(.prgvtl7pl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24v18.5H24");
}

:global(.q2yv-wrex) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24A18.5 18.5 0 0 1 24 5.5A18.5 18.5 0 0 1 42.5 24A18.5 18.5 0 0 1 24 42.5");
}

</style>

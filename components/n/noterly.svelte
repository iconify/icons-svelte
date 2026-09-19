<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ldtxoib6p"/><path class="q60tjhb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:noterly" {...props}></Icon>
<style>
:global(.ldtxoib6p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26 24h16.5v16.5c0 1.108-.892 2-2 2H24V26c0-1.108.892-2 2-2");
}

:global(.q60tjhb_u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24L24 42.5C13.783 42.5 5.5 34.217 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24");
}

</style>

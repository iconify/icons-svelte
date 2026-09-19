<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x1yz1qpgl"/><path class="b5_jxvbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fastmail" {...props}></Icon>
<style>
:global(.b5_jxvbdz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 36V12L24 24");
}

:global(.x1yz1qpgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 12l-37 24h35a2 2 0 0 0 2-2Z");
}

</style>

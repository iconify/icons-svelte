<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sxhbn6bmj"/><circle class="ixa2ttbsg"/><path class="cd4r4wbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:metronome" {...props}></Icon>
<style>
:global(.cd4r4wbrt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.01 30.01l9.19 9.19M17.99 17.99L8.8 8.8");
}

:global(.ixa2ttbsg) {
  cx: 24px;
  cy: 24px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sxhbn6bmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.51 21.51 0 0 0 2.5 24M24 45.5A21.51 21.51 0 0 0 45.5 24");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="tg8vlotfd"/><circle class="q-ay7ac-d"/><circle class="qfhjmybex"/><circle class="dr57fdc0a"/><circle class="g9pn9xbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:luxerone" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.dr57fdc0a) {
  cx: 32.959px;
  cy: 10.829px;
  r: 0.75px;
  fill: currentColor;
}

:global(.g9pn9xbos) {
  cx: 15.041px;
  cy: 10.829px;
  r: 0.75px;
  fill: currentColor;
}

:global(.q-ay7ac-d) {
  cx: 15.041px;
  cy: 37.171px;
  r: 0.75px;
  fill: currentColor;
}

:global(.qfhjmybex) {
  cx: 32.959px;
  cy: 37.171px;
  r: 0.75px;
  fill: currentColor;
}

:global(.tg8vlotfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.843 16.419l10.314 15.162m0-15.162L18.843 31.581");
}

</style>

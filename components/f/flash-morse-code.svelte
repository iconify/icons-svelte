<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t2d5dwbrg"/><circle class="elmf8_b8e"/><circle class="i58ae2blo"/><circle class="i5rdw2b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flash-morse-code" {...props}></Icon>
<style>
:global(.elmf8_b8e) {
  cx: 16.2px;
  cy: 8.4px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i58ae2blo) {
  cx: 31.8px;
  cy: 8.4px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i5rdw2b1f) {
  cx: 31.8px;
  cy: 24px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t2d5dwbrg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 20.1za3.9 3.9 0 0 1 3.9 3.9v15.6a3.9 3.9 0 0 1-7.8 0V24a3.9 3.9 0 0 1 3.9-3.9");
}

</style>

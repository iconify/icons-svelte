<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ignk1acfm"/><circle class="sc07fvbrb"/><circle class="dwrtslbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-music" {...props}></Icon>
<style>
:global(.dwrtslbtb) {
  cx: 38.739px;
  cy: 28.828px;
  r: 2.074px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ignk1acfm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.688 21.679C1.976 18.489 7.88 4.55 17.323 5.55c13.562 1.437 18.169 20.827-2.048 36.95");
}

:global(.sc07fvbrb) {
  cx: 38.739px;
  cy: 14.441px;
  r: 2.074px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

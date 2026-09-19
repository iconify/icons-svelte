<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hw5v2-bxt"/><circle class="v-2glkbwo"/><path class="mdk2m-bsb"/><circle class="bpt4skbvy"/><path class="jfnjrubqe"/><circle class="khev9tb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hide-my-applist" {...props}></Icon>
<style>
:global(.bpt4skbvy) {
  cx: 16px;
  cy: 14px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hw5v2-bxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 43.5h23a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4m15-39v39m-7-19.5h7");
}

:global(.jfnjrubqe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 34h7");
}

:global(.khev9tb-c) {
  cx: 16px;
  cy: 34px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mdk2m-bsb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.5 14h7");
}

:global(.v-2glkbwo) {
  cx: 16px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="a_h1hec3w"/><path class="l78v5tbns"/></g><path class="uph4zqc9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-google-9" {...props}></Icon>
<style>
:global(.a_h1hec3w) {
  cx: 24px;
  cy: 22.5px;
  r: 3px;
}

:global(.l78v5tbns) {
  d: path("M21.333 27.389c.445.667 1.223 1.111 2.445 1.111H24c1.667 0 3-1.333 3-3v-3");
}

:global(.uph4zqc9i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="fcggsugyz"/><path class="hcborccui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mvgo" {...props}></Icon>
<style>
:global(.fcggsugyz) {
  cx: 34.25px;
  cy: 24px;
  r: 10.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hcborccui) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24c0 5.66-4.59 10.25-10.25 10.25S3.5 29.66 3.5 24s4.59-10.25 10.25-10.25a10.25 10.25 0 0 1 9.055 5.442M13.75 24H24");
}

</style>

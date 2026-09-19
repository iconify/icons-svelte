<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="l1b5m0y8g"/><path class="p7bukccef"/><path class="pp9qnwbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dianping" {...props}></Icon>
<style>
:global(.l1b5m0y8g) {
  cx: 19.637px;
  cy: 12.698px;
  r: 7.196px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p7bukccef) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.806 9.437a12.598 12.598 0 0 1-24.337 6.52");
}

:global(.pp9qnwbwg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.718 42.499c-2.058-7.68 2.5-15.575 10.18-17.633q0 0 0 0c7.68-2.058 15.575 2.5 17.633 10.18q0 0 0 0");
}

</style>

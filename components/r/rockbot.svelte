<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s5pqyubzc"/><circle class="nosz94bdb"/><path class="jcare90hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rockbot" {...props}></Icon>
<style>
:global(.jcare90hd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 10.03h10.51c3.87 0 6.99 3.136 6.99 6.989s-3.12 6.989-6.99 6.989m1 0c3.87 0 6.99 3.12 6.99 6.973s-3.12 6.99-6.99 6.99H24v-9.983");
}

:global(.nosz94bdb) {
  cx: 23.996px;
  cy: 24.001px;
  r: 3.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s5pqyubzc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 20.028V10.03m11.511 13.978H27.98m-7.96 0h-7.547c-3.853 0-6.973-3.136-6.973-6.99s3.12-6.988 6.973-6.988H24m-8.341 13.971L7.085 37.965");
}

</style>

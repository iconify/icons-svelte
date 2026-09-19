<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tc5jlybxw"/><circle class="mkmfdbwjf"/><circle class="j-_r13bil"/><circle class="s3vrgcb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:codmon" {...props}></Icon>
<style>
:global(.j-_r13bil) {
  cx: 15.5px;
  cy: 21.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mkmfdbwjf) {
  cx: 38px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s3vrgcb9j) {
  cx: 22px;
  cy: 21.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tc5jlybxw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.178 32.16A15.5 15.5 0 0 1 20 39.5c-8.56 0-15.5-6.94-15.5-15.5S11.44 8.5 20 8.5a15.5 15.5 0 0 1 13.177 7.338");
}

</style>

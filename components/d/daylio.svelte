<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="byyvn4y9n"/><ellipse class="relochoce"/><ellipse class="ahmjtvmws"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:daylio" {...props}></Icon>
<style>
:global(.ahmjtvmws) {
  cx: 35.89px;
  cy: 22.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.75px;
  ry: 2.39px;
}

:global(.byyvn4y9n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.11 32.44l21.78.2c-1.07 10.49-22.12 8.64-21.78-.2");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.relochoce) {
  cx: 12.11px;
  cy: 22.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.75px;
  ry: 2.39px;
}

</style>

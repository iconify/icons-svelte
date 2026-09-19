<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="edi79mb8h"/><path class="s8q59gb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mvvapp" {...props}></Icon>
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

:global(.edi79mb8h) {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s8q59gb4o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.55 35.79c1.66.77 3.5 1.21 5.45 1.21c7.18 0 13-5.82 13-13s-5.82-13-13-13s-13 5.82-13 13c0 1.95.44 3.79 1.21 5.45");
}

</style>

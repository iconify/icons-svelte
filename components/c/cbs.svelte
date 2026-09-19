<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="b1w5hzzmd"/><circle class="p015yvbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cbs" {...props}></Icon>
<style>
:global(.b1w5hzzmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.15c-9.052 0-16.981 4.736-21.5 11.85C7.019 31.114 14.948 35.85 24 35.85S40.981 31.113 45.5 24C40.981 16.886 33.052 12.15 24 12.15");
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

:global(.p015yvbcc) {
  cx: 24px;
  cy: 24px;
  r: 11.849px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

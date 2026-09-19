<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="pt9ns81ic"/><path class="lna-g7wmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lineage-audiofx" {...props}></Icon>
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

:global(.lna-g7wmc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.219 29.781l-9.421 9.421m20.98-9.424L39.2 39.2m-7.547-18.08l1.237-4.704a1.07 1.07 0 0 0-1.305-1.305l-4.703 1.235");
}

:global(.pt9ns81ic) {
  cx: 24px;
  cy: 24px;
  r: 8.176px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

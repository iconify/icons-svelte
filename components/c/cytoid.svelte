<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="db5arjb0l"/><path class="xpnh-q2dv"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cytoid" {...props}></Icon>
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

:global(.db5arjb0l) {
  cx: 24px;
  cy: 24px;
  r: 8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xpnh-q2dv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.5 24c0 6.351-5.149 11.5-11.5 11.5h0c-6.351 0-11.5-5.149-11.5-11.5h0c0-6.351 5.149-11.5 11.5-11.5h0c6.351 0 11.5 5.149 11.5 11.5");
}

</style>

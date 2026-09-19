<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ug35shkdh"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:currency-euro" {...props}></Icon>
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

:global(.ug35shkdh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.525 30.695a5.89 5.89 0 0 1-4.516 2.102h0a5.9 5.9 0 0 1-5.9-5.9v-5.794a5.9 5.9 0 0 1 5.9-5.9h0a5.89 5.89 0 0 1 4.535 2.125M15.91 21.862h6.598M15.91 26.18h6.598");
}

</style>

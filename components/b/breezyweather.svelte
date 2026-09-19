<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nrzcrmb4v"/><circle class="n8j_1t6qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:breezyweather" {...props}></Icon>
<style>
:global(.n8j_1t6qc) {
  cx: 24px;
  cy: 24px;
  r: 12.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nrzcrmb4v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24c0-5.9 4.8-10.8 10.8-10.8S45.6 18 45.6 24H24.1Zm0 0c5.9 0 10.8 4.8 10.8 10.8S30 45.6 24 45.6V24.1Zm0 0c0 5.9-4.8 10.8-10.8 10.8S2.5 29.9 2.5 24zm0 0c-5.9 0-10.8-4.8-10.8-10.8S18.1 2.5 24 2.5z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zqrikt46n"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nemid" {...props}></Icon>
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

:global(.zqrikt46n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.789 23.905h-19.22m-2.072 2.074v2.979m21.292-5.053a4.86 4.86 0 1 1 1.032 2.998M13.34 24.379v4.375m-2.771-4.849a1.892 1.892 0 0 0-2.071 2.074");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jpl_urmou"/><path class="sj6e0-mnr"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mbandhan-2" {...props}></Icon>
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

:global(.jpl_urmou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.577 2.526a17.5 17.5 0 0 1 6.673 13.749v0a17.5 17.5 0 0 1-17.5 17.5a17.5 17.5 0 0 1-8.934-2.452");
}

:global(.sj6e0-mnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.991 29.672a17.5 17.5 0 0 1-6.24-13.397A17.5 17.5 0 0 1 24 2.871");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="euyqkkb5d"/><path class="z32u-jboz"/><path class="o95u8d_ts"/><path class="r229vbbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alight-motion" {...props}></Icon>
<style>
:global(.euyqkkb5d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 28.33a19.5 19.5 0 0 0-39 0");
}

:global(.o95u8d_ts) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.25 39.17a11.227 11.227 0 1 0 0-22.454");
}

:global(.r229vbbyb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.602 38.222a14.637 14.637 0 1 0-20.7-20.7");
}

:global(.z32u-jboz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.47 32.593a6.923 6.923 0 0 0 9.79-9.79");
}

</style>

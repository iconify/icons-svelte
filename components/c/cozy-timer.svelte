<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="h556c6bik"/><circle class="meiz9bcpx"/><circle class="bye4gxbbp"/><circle class="oqldv0y3h"/><path class="bqzlp77zu"/><circle class="cpk0fnbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cozy-timer" {...props}></Icon>
<style>
:global(.bqzlp77zu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24l-8.84-8.84");
}

:global(.bye4gxbbp) {
  cx: 39.5px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
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

:global(.h556c6bik) {
  cx: 24px;
  cy: 39.5px;
  r: 0.75px;
  fill: currentColor;
}

:global(.meiz9bcpx) {
  cx: 8.5px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

:global(.oqldv0y3h) {
  cx: 24px;
  cy: 8.5px;
  r: 0.75px;
  fill: currentColor;
}

</style>

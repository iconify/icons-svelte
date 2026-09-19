<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jcb67ab5u"/><path class="f710l3bib"/><rect class="k1qs_h7jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:berichtenbox" {...props}></Icon>
<style>
:global(.f710l3bib) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.552 14.5L24 25.589L8.448 14.5m8.09 11.656L8 33.5m32 0l-8.538-7.344");
}

:global(.jcb67ab5u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.72 10.5h4.56v8.554h-4.56z");
}

:global(.k1qs_h7jn) {
  width: 39px;
  height: 27px;
  x: 4.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>

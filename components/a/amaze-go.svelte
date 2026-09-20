<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="b7uiw0jhb"/><path class="ja1r1_5wb"/><path class="g1_582boh"/><path class="kphsngbeb"/><path class="xrseqob1g"/><path class="jlyultbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amaze-go" {...props}></Icon>
<style>
:global(.b7uiw0jhb) {
  d: path("M17.513 30.597H30.64V9.667");
}

:global(.g1_582boh) {
  d: path("m19.013 18.765l-1.491-2.57l-1.492 2.57m21.18-7.902v20.93m1.492-2.57l-1.491 2.57l-1.492-2.57");
}

:global(.ja1r1_5wb) {
  d: path("m32.13 12.237l-1.491-2.57l-1.492 2.57m-11.625 3.959v7.879h-6.48l-.001 13.068h26.17");
}

:global(.jlyultbfy) {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

:global(.kphsngbeb) {
  d: path("M24.125 25.31V10.981H11.04v6.633");
}

:global(.xrseqob1g) {
  d: path("m25.616 22.74l-1.491 2.57l-1.492-2.57");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

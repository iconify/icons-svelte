<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="pr52f_b5y"><path class="z7lihhmfc"/><path class="rxz6qsolw"/><circle class="ug_bo6buy"/><path class="utyjo0ige"/><path class="webygcbbu"/><circle class="kzs11-8fd"/><circle class="fi6rh2b3i"/><path class="dd9y9ubue"/><path class="pzoi-jrsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pceemu" {...props}></Icon>
<style>
:global(.dd9y9ubue) {
  stroke-miterlimit: 2.046;
  d: path("M9.497 29.096v-3.088m-1.544 1.544h3.088");
}

:global(.fi6rh2b3i) {
  cx: 39.221px;
  cy: 29.067px;
  r: 1.483px;
  stroke-linejoin: round;
}

:global(.kzs11-8fd) {
  cx: 33.2px;
  cy: 29.067px;
  r: 1.483px;
  stroke-linejoin: round;
}

:global(.pr52f_b5y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

:global(.pzoi-jrsd) {
  stroke-linejoin: round;
  d: path("M20.231 29.11h1.634m3.438 0h1.633");
}

:global(.rxz6qsolw) {
  stroke-linejoin: round;
  d: path("M17.955 14.823s-2.643.102-5.569.331c-1.034.081-2.71.24-3.735.396a47 47 0 0 0-3.329.638c-1.011.231-1.822 1.298-1.822 2.336v13.721c0 1.038.84 1.943 1.876 1.991c2.39.111 7.382.267 16.75.286c1.035.002 2.715.002 3.753 0c9.37-.019 14.362-.175 16.75-.286c1.034-.048 1.871-.953 1.871-1.99V18.524c0-1.038-.81-2.105-1.822-2.336a47 47 0 0 0-3.329-.638c-1.026-.156-2.701-.315-3.736-.396c-2.925-.229-5.568-.331-5.568-.331");
}

:global(.ug_bo6buy) {
  cx: 9.497px;
  cy: 27.552px;
  r: 3.019px;
  stroke-linejoin: round;
}

:global(.utyjo0ige) {
  stroke-linejoin: round;
  d: path("M36.926 32.17L24 32.175l-12.925-.005a4.9 4.9 0 0 0 3.308-4.618a4.885 4.885 0 0 0-4.886-4.885a4.93 4.93 0 0 0-2.87.94l-.004-5.448h11.332m12.09 0h11.332l-.003 5.448v3.204");
}

:global(.webygcbbu) {
  stroke-linejoin: round;
  d: path("M42.329 29.067c0 1.716-1.37 3.108-3.06 3.108h-6.118c-1.69 0-3.059-1.392-3.059-3.108s1.37-3.108 3.06-3.108h6.118c1.689 0 3.059 1.392 3.059 3.108");
}

:global(.z7lihhmfc) {
  stroke-linejoin: round;
  d: path("M17.955 19.554v-6.021s1.285-.056 6.045-.056s6.045.056 6.045.056v6.021s.322 6.893-6.045 6.893s-6.045-6.893-6.045-6.893");
}

</style>

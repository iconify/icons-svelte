<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o7xcj9b5m"/><path class="iu3j18b-o"/><path class="izkbhz86a"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:extractor-outline-thin" {...props}></Icon>
<style>
:global(.cfyvl-o0i) {
  d: path("M16 12h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iu3j18b-o) {
  d: path("M9 8h4");
}

:global(.izkbhz86a) {
  d: path("M9 12h4");
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.o7xcj9b5m) {
  d: path("M13 2H6v19h8");
}

</style>

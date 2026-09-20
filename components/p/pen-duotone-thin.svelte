<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="duz1sfbva"/><path class="wloabnb9u"/><path class="w2_t-sslc"/><path class="kg5ylpb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pen-duotone-thin" {...props}></Icon>
<style>
:global(.duz1sfbva) {
  fill: currentColor;
  d: path("m8 16 9 -9 3 3 -9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kg5ylpb0c) {
  d: path("M8 16v3");
}

:global(.w2_t-sslc) {
  d: path("m8 16 -3 3h6");
}

:global(.wloabnb9u) {
  d: path("m8 16 9 -9 3 3 -9 9Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is1bv_axc"/><path class="feqdbpj9t"/><path class="tc8fh3off"/><path class="on73k30pq"/><path class="x5tg-9bgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:replan-outline-thin" {...props}></Icon>
<style>
:global(.feqdbpj9t) {
  d: path("m3 17 6 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is1bv_axc) {
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.on73k30pq) {
  d: path("M16 9h4");
}

:global(.tc8fh3off) {
  d: path("M14 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.x5tg-9bgp) {
  d: path("M16 13h4");
}

</style>

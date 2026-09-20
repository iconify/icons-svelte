<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfcdzc65k"/><path class="z5135gcut"/><path class="o7mqvuj4j"/><path class="kdmnrabtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:end-to-end-outline-thin" {...props}></Icon>
<style>
:global(.dfcdzc65k) {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdmnrabtq) {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.o7mqvuj4j) {
  d: path("M15 12.5V15h-2.5");
}

:global(.z5135gcut) {
  d: path("m8 8 4 4");
}

</style>

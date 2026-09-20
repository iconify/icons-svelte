<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e81u5lw0o"/><path class="uso-o7_ft"/><path class="wmg5scbww"/><path class="cwy6p7vpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heart-zone-duotone-thin" {...props}></Icon>
<style>
:global(.cwy6p7vpw) {
  d: path("M20 10v10");
}

:global(.e81u5lw0o) {
  fill: currentColor;
  d: path("M2 9a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
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

:global(.uso-o7_ft) {
  d: path("M2 9a3 3 0 0 1 6 0 3 3 0 0 1 6 0l-6 6Z");
}

:global(.wmg5scbww) {
  d: path("M17 14v6");
}

</style>

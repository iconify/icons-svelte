<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yde2vxf3y"/><path class="lpqu47bxv"/><path class="w7e53rb8m"/><path class="mqtixbwqo"/><path class="bso0bbbqi"/><path class="z8g2jgblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:portion-duotone-thin" {...props}></Icon>
<style>
:global(.bso0bbbqi) {
  d: path("M21 8A9 9 0 0 1 3 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lpqu47bxv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 8A9 9 0 0 1 3 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.w7e53rb8m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yde2vxf3y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>

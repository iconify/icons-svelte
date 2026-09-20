<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="txe4klbyh"/><path class="plajqrbag"/><path class="mv9_3430k"/><path class="c-q_c4t2g"/><path class="dt4wyoqho"/><path class="fz6e7vbzb"/><path class="dc0xg9bgf"/><path class="zqnyy8bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:filter-metadata-duotone-regular" {...props}></Icon>
<style>
:global(.c-q_c4t2g) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 4H3l7 7v7h4v-7l7 -7h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dc0xg9bgf) {
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.dt4wyoqho) {
  d: path("M9 4H3l7 7v7h4v-7l7 -7h-6");
}

:global(.fz6e7vbzb) {
  d: path("M5 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mv9_3430k) {
  fill: currentColor;
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.plajqrbag) {
  fill: currentColor;
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.txe4klbyh) {
  fill: currentColor;
  d: path("M5 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zqnyy8bad) {
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

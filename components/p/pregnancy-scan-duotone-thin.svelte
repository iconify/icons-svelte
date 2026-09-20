<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mws_ge37e"/><path class="wey2ko0vh"/><path class="xekk022fw"/><path class="jnf_2db5t"/><path class="gl3o38_gx"/><path class="z8c0a6b1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pregnancy-scan-duotone-thin" {...props}></Icon>
<style>
:global(.gl3o38_gx) {
  d: path("M8 21h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.mws_ge37e) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wey2ko0vh) {
  fill: currentColor;
  d: path("M9 13a4 4 0 0 1 6 -5c0 4 -2 6 -6 5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xekk022fw) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.z8c0a6b1x) {
  d: path("M9 13a4 4 0 0 1 6 -5c0 4 -2 6 -6 5");
}

</style>

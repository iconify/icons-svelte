<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yde2vxf3y"/><path class="ynn2b5v5b"/><path class="s0ufku7vs"/><path class="xxgbubv3x"/><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-table-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mei2sobow) {
  d: path("M19 8v12");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.s0ufku7vs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

:global(.xxgbubv3x) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

:global(.yde2vxf3y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ynn2b5v5b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

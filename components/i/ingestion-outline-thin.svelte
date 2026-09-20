<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nvzooz8re"/><path class="mdjxzrmlu"/><path class="pus8sccta"/><path class="ujxlr6_3m"/><path class="cz-gg2_-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ingestion-outline-thin" {...props}></Icon>
<style>
:global(.cz-gg2_-j) {
  d: path("m14 8 2 2 2 -2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdjxzrmlu) {
  d: path("M8 3v7");
}

:global(.nvzooz8re) {
  d: path("M4 18.5A2.5 2.5 0 0 1 6.5 16h11a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-11A2.5 2.5 0 0 1 4 18.5");
}

:global(.pus8sccta) {
  d: path("m6 8 2 2 2 -2");
}

:global(.ujxlr6_3m) {
  d: path("M16 3v7");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ft030md1w"/><path class="qok4og0tb"/><path class="jct8clbxu"/><path class="skbifdbcx"/><path class="hnix93blm"/><path class="gpzsx6dgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-power-duotone-thin" {...props}></Icon>
<style>
:global(.ft030md1w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gpzsx6dgy) {
  d: path("M16.5 10v5");
}

:global(.hnix93blm) {
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jct8clbxu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 10v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qok4og0tb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.68 12.82a4.5 4.5 0 1 1 -6.36 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>

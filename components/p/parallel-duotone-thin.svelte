<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e2lswlyjr"/><path class="ty7e9cb8v"/><path class="boqmo37co"/><path class="amid48b6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parallel-duotone-thin" {...props}></Icon>
<style>
:global(.amid48b6f) {
  d: path("m8 12 4 4h9");
}

:global(.boqmo37co) {
  d: path("M3 12h5l4 -4h9");
}

:global(.e2lswlyjr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h5l4 -4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ty7e9cb8v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 4 4h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

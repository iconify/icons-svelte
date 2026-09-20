<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3ui8tboa"/><path class="rgv-h7b7q"/><path class="h_ozghejt"/><path class="j4cr2gb0p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cli-duotone-thin" {...props}></Icon>
<style>
:global(.h_ozghejt) {
  d: path("m4 7 5 5 -5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4cr2gb0p) {
  d: path("M11 17h9");
}

:global(.rgv-h7b7q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 17h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z3ui8tboa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j53em0blo"/><path class="rxnebibzp"/><path class="hsnj9o-9y"/><path class="zky4dibyk"/><path class="rjl8fe1sw"/><path class="qq9-4ficr"/><path class="jkuojibnm"/><path class="o1o-p0bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:admission-webhook-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j53em0blo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.o1o-p0bmq) {
  d: path("m19 7 -4 4h3l-4 4");
}

:global(.qq9-4ficr) {
  d: path("m4 13 9 -9");
}

:global(.rjl8fe1sw) {
  d: path("M4 6v14");
}

:global(.rxnebibzp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 13 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zky4dibyk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 7 -4 4h3l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

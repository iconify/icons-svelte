<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eri9pjq"/><path class="ta4vmeb9o"/><path class="ook98ebgg"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="c5gaambbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prompt-cache-hit-duotone-thin" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.c5gaambbs) {
  d: path("M13.5 9.5 11 12h2.5L11 14.5");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.e6eri9pjq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ook98ebgg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 9.5 11 12h2.5L11 14.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ta4vmeb9o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

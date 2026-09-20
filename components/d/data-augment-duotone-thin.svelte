<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="epwe3rblo"/><path class="bt_2bvgpa"/><path class="d9d90wspe"/><path class="qn7wn8bdv"/><path class="f9f62bbix"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-augment-duotone-thin" {...props}></Icon>
<style>
:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d9d90wspe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.epwe3rblo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f9f62bbix) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 12v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.ndv19xfog) {
  d: path("M3 14h10");
}

:global(.nlg6c6b-z) {
  d: path("M18.5 12v4");
}

:global(.qn7wn8bdv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qypknac_m) {
  d: path("M16.5 14h4");
}

:global(.r0_oskb4z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

</style>

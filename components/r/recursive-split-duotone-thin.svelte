<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ljo-5rbrq"/><path class="hklbkzb4u"/><path class="wmcccebtm"/><path class="b00nkwbbm"/><path class="vmf78ibki"/><path class="kzxacebng"/><path class="c7dgfu7wx"/><path class="lgyhdeb-s"/><path class="j1kezkxcy"/><path class="ezp0d4btt"/><path class="gnit4mb6c"/><path class="lkpe2ldcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recursive-split-duotone-thin" {...props}></Icon>
<style>
:global(.b00nkwbbm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c7dgfu7wx) {
  d: path("M2 4h20");
}

:global(.ezp0d4btt) {
  d: path("M2 16h3");
}

:global(.gnit4mb6c) {
  d: path("M7.5 16h3");
}

:global(.hklbkzb4u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 10h8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j1kezkxcy) {
  d: path("M13.5 10H22");
}

:global(.kzxacebng) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgyhdeb-s) {
  d: path("M2 10h8.5");
}

:global(.ljo-5rbrq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lkpe2ldcq) {
  d: path("M13.5 16H22");
}

:global(.vmf78ibki) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wmcccebtm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 10H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kvle2skfl"/><path class="ns4jmsbxl"/><path class="dgamp4bkk"/><path class="fyea5htjc"/><path class="c4axibc2h"/><path class="uo9ro-b5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:citation-check-duotone-thin" {...props}></Icon>
<style>
:global(.c4axibc2h) {
  d: path("M8 3v4");
}

:global(.dgamp4bkk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 14 5 5L20 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fyea5htjc) {
  d: path("M4 3v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kvle2skfl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ns4jmsbxl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uo9ro-b5p) {
  d: path("m4 14 5 5L20 8");
}

</style>

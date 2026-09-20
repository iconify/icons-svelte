<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ooo8twz0m"/><path class="tu2_m5dvw"/><path class="id4vqxf8c"/><path class="qlw91sbif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overfit-gap-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.id4vqxf8c) {
  d: path("m4 14 5 -5h11");
}

:global(.ooo8twz0m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 14 5 -5h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qlw91sbif) {
  d: path("m4 19 5 -5h4l4 4");
}

:global(.tu2_m5dvw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 19 5 -5h4l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

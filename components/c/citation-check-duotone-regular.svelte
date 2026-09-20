<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="euq2huu8d"/><path class="qi9dmy_br"/><path class="uyjm3pbni"/><path class="fyea5htjc"/><path class="c4axibc2h"/><path class="uo9ro-b5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:citation-check-duotone-regular" {...props}></Icon>
<style>
:global(.c4axibc2h) {
  d: path("M8 3v4");
}

:global(.euq2huu8d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fyea5htjc) {
  d: path("M4 3v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qi9dmy_br) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uo9ro-b5p) {
  d: path("m4 14 5 5L20 8");
}

:global(.uyjm3pbni) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 14 5 5L20 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

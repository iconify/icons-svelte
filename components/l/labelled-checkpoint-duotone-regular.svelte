<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8bsosbbf"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="wl7bxfbmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:labelled-checkpoint-duotone-regular" {...props}></Icon>
<style>
:global(.c8bsosbbf) {
  fill: currentColor;
  d: path("M9 7h3l3 3 -3 3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wl7bxfbmv) {
  d: path("M9 7h3l3 3 -3 3H9Z");
}

</style>

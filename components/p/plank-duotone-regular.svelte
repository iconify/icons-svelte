<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wznabhb2m"/><path class="qvo5bxbje"/><path class="c-s-008ep"/><path class="m54fd64oa"/><path class="xdhl9rnnf"/><path class="bhkm33b7x"/><path class="x8_u9-97v"/><path class="zpp3fehhr"/><path class="zuuhu6bzg"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plank-duotone-regular" {...props}></Icon>
<style>
:global(.bhkm33b7x) {
  d: path("M2 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.c-s-008ep) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m54fd64oa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvo5bxbje) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 8 4 4h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wznabhb2m) {
  fill: currentColor;
  d: path("M2 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8_u9-97v) {
  d: path("m6 8 4 4h10");
}

:global(.xdhl9rnnf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpp3fehhr) {
  d: path("M10 12v3");
}

:global(.zuuhu6bzg) {
  d: path("M6 15h6");
}

</style>

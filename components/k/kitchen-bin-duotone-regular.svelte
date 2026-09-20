<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t3ckr4baw"/><path class="aqrf9ebcv"/><path class="y_c6uxv0i"/><path class="qll6019sr"/><path class="odlchqg5v"/><path class="vhnbtvbtn"/><path class="h2-rujbru"/><path class="azrfjy1oo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kitchen-bin-duotone-regular" {...props}></Icon>
<style>
:global(.aqrf9ebcv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.azrfjy1oo) {
  d: path("M14 5v3");
}

:global(.h2-rujbru) {
  d: path("M10 5v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.odlchqg5v) {
  d: path("M6 9c0.5 4 1 8 2 11h8c1 -3 1.5 -7 2 -11");
}

:global(.qll6019sr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3ckr4baw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9c0.5 4 1 8 2 11h8c1 -3 1.5 -7 2 -11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.y_c6uxv0i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

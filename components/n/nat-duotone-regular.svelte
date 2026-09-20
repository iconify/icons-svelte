<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="em4zwn5rk"/><path class="aubpara-q"/><path class="f0c00-bny"/><path class="myhwu1bcf"/><path class="bgv4bs7dd"/><path class="otb2wbb6e"/><path class="wj4cfmbhq"/><path class="ms85c68gf"/><path class="i6ydbdc_n"/><path class="eud-3ptuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nat-duotone-regular" {...props}></Icon>
<style>
:global(.aubpara-q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bgv4bs7dd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.em4zwn5rk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 4h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eud-3ptuk) {
  d: path("M15 12h7");
}

:global(.f0c00-bny) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i6ydbdc_n) {
  d: path("m9 4 6 6v4l-6 6");
}

:global(.ms85c68gf) {
  d: path("M2 20h7");
}

:global(.myhwu1bcf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 4 6 6v4l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.otb2wbb6e) {
  d: path("M2 4h7");
}

:global(.wj4cfmbhq) {
  d: path("M2 12h7");
}

</style>

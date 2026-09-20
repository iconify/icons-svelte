<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ricsvm5vg"/><path class="p56aeiufb"/><path class="w2-v5h90u"/><path class="u_mz2vbve"/><path class="ricsl-blc"/><path class="wneoubc6n"/><path class="fzby91bau"/><path class="ka7-gu1bd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:broadcast-duotone-thin" {...props}></Icon>
<style>
:global(.fzby91bau) {
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ka7-gu1bd) {
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
}

:global(.p56aeiufb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.ricsvm5vg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u_mz2vbve) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w2-v5h90u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

</style>

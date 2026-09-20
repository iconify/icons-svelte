<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipj8mpsia"/><path class="l0tg10jig"/><path class="u01hv34_m"/><path class="oqd-rtxrg"/><path class="ricsl-blc"/><path class="wneoubc6n"/><path class="fzby91bau"/><path class="ka7-gu1bd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:broadcast-duotone-regular" {...props}></Icon>
<style>
:global(.fzby91bau) {
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
}

:global(.ipj8mpsia) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 12v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ka7-gu1bd) {
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
}

:global(.l0tg10jig) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqd-rtxrg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5.42 7.61a7 7 0 0 1 13.16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.u01hv34_m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.24 8.63a4 4 0 0 1 7.5 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

</style>

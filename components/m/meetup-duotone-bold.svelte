<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ef0y9bcrl"/><path class="fsuht_b8c"/><path class="ietrdurnc"/><path class="acyg6nb1v"/><path class="ibxg-pb4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:meetup-duotone-bold" {...props}></Icon>
<style>
:global(.acyg6nb1v) {
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ef0y9bcrl) {
  fill: currentColor;
  d: path("M12 21s-7 -7 -7 -11a7 7 0 0 1 14 0c0 4 -7 11 -7 11");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fsuht_b8c) {
  fill: currentColor;
  d: path("M10 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ibxg-pb4c) {
  d: path("M9 13a3 3 0 0 1 6 0");
}

:global(.ietrdurnc) {
  d: path("M12 21s-7 -7 -7 -11a7 7 0 0 1 14 0c0 4 -7 11 -7 11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

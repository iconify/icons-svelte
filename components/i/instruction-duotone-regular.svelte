<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxow7abeb"/><path class="gf0hswvuq"/><path class="li29erb7r"/><path class="abnm6smsv"/><path class="u84sg0ngq"/><path class="a2e335b1o"/><path class="h857n5bhq"/><path class="fmjpvzbts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:instruction-duotone-regular" {...props}></Icon>
<style>
:global(.a2e335b1o) {
  d: path("M11 10h5");
}

:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.fmjpvzbts) {
  d: path("M11 14h5");
}

:global(.gf0hswvuq) {
  fill: currentColor;
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h857n5bhq) {
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.li29erb7r) {
  fill: currentColor;
  d: path("M8 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u84sg0ngq) {
  d: path("M8 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yxow7abeb) {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

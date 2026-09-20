<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u8h66mbjf"/><path class="rno54ybbk"/><path class="eu9kkgbdm"/><path class="m27ljac1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:laser-duotone-regular" {...props}></Icon>
<style>
:global(.eu9kkgbdm) {
  d: path("M9 12h12");
}

:global(.m27ljac1c) {
  d: path("m18 9 3 3 -3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rno54ybbk) {
  d: path("M3 7h6v10H3Z");
}

:global(.u8h66mbjf) {
  fill: currentColor;
  d: path("M3 7h6v10H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

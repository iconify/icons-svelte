<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ss0frm8tj"/><path class="r182r524c"/><path class="mb7g-z76v"/><path class="avnm-g99q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hard-limit-outline-regular" {...props}></Icon>
<style>
:global(.avnm-g99q) {
  d: path("m14 12 -4 4");
}

:global(.mb7g-z76v) {
  d: path("m10 12 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.ss0frm8tj) {
  d: path("M13.5 4H16a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h2.5");
}

</style>

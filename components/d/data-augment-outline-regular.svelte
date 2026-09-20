<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ndv19xfog"/><path class="qypknac_m"/><path class="nlg6c6b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-augment-outline-regular" {...props}></Icon>
<style>
:global(.j835zw5-z) {
  d: path("M3 9h18");
}

:global(.mg7aqnbsf) {
  d: path("M3 4h18");
}

:global(.ndv19xfog) {
  d: path("M3 14h10");
}

:global(.nlg6c6b-z) {
  d: path("M18.5 12v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qypknac_m) {
  d: path("M16.5 14h4");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

</style>

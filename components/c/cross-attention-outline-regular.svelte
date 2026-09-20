<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cross-attention-outline-regular" {...props}></Icon>
<style>
:global(.flq2w3bwj) {
  d: path("m9.5 9.5 5 5");
}

:global(.k5f0ncbhf) {
  d: path("m14.5 9.5 -5 5");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

</style>

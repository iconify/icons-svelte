<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rxdjtqbaf"/><path class="v1nby09ur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:a-arrow-down-two-tone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rxdjtqbaf) {
  stroke-opacity: 0.4;
  d: path("M2 19L7 5L12 19M3.7857 14L10.2143 14");
}

:global(.v1nby09ur) {
  d: path("M19 9L19 19M16 16L19 19L22 16");
}

</style>

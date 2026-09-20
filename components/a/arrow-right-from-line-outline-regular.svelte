<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c_pe6njtz"/><path class="bzecsub_a"/><path class="u8aszkb6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-right-from-line-outline-regular" {...props}></Icon>
<style>
:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.c_pe6njtz) {
  d: path("M4 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u8aszkb6i) {
  d: path("m16 8 4 4 -4 4");
}

</style>

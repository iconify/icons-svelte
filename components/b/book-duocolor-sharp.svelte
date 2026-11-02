<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gq-ihhwqb"/><path class="pg8i97nqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:book-duocolor-sharp" {...props}></Icon>
<style>
:global(.gq-ihhwqb) {
  stroke-opacity: 0.4;
  d: path("M7 21h10v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pg8i97nqv) {
  d: path("M7 17h12V3H5v16m2-2a2 2 0 1 0 0 4");
}

</style>

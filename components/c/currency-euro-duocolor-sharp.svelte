<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u3esjiziv"/><path class="gxzraf6oz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-euro-duocolor-sharp" {...props}></Icon>
<style>
:global(.gxzraf6oz) {
  d: path("M19 7a7.071 7.071 0 1 0 0 10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u3esjiziv) {
  stroke-opacity: 0.4;
  d: path("M5 10h2m0 0h6m-8 4h2m0 0h6");
}

</style>

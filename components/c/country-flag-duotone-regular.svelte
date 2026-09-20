<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ctz1arb4t"/><path class="g1bdqebqy"/><path class="clcqrbcsg"/><path class="a_-94rbje"/><path class="f9uxp9ptq"/><path class="he6k4tqrw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:country-flag-duotone-regular" {...props}></Icon>
<style>
:global(.a_-94rbje) {
  d: path("M5 2v20");
}

:global(.clcqrbcsg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8.5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ctz1arb4t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f9uxp9ptq) {
  d: path("M5 4h14v9H5");
}

:global(.g1bdqebqy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4h14v9H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.he6k4tqrw) {
  d: path("M5 8.5h14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

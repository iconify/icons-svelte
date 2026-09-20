<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pqgcmcahi"/><path class="c587bq8qn"/><path class="x9zn9l6tg"/><path class="tt1n5wbag"/><path class="e7pgrp-wx"/><path class="wp75hkmty"/><path class="rutulxlvn"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gc-pause-duotone-regular" {...props}></Icon>
<style>
:global(.c587bq8qn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pqgcmcahi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rutulxlvn) {
  d: path("M14 7v10");
}

:global(.tt1n5wbag) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wp75hkmty) {
  d: path("M11 7v10");
}

:global(.x9zn9l6tg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rh6cspb3h"/><path class="l2k0-c9-j"/><path class="xj_kqitvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:juice-outline-regular" {...props}></Icon>
<style>
:global(.l2k0-c9-j) {
  d: path("m6 8 5 -5 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rh6cspb3h) {
  d: path("M6 8v13h10V8Z");
}

:global(.xj_kqitvx) {
  d: path("m13 8 5 -5");
}

</style>

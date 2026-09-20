<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pywr_yykw"/><path class="m0hvambgh"/><path class="c2-gs7b7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flash-sale-outline-regular" {...props}></Icon>
<style>
:global(.c2-gs7b7d) {
  d: path("m15 9 -3 3h2.5l-3 3");
}

:global(.m0hvambgh) {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pywr_yykw) {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

</style>

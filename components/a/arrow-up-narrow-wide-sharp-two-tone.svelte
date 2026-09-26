<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c0f8r7r7i"/><path class="g3likac1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-narrow-wide-sharp-two-tone" {...props}></Icon>
<style>
:global(.c0f8r7r7i) {
  stroke-opacity: 0.4;
  d: path("M13 6L17 6M13 10L19 10M13 14L21 14M13 18L23 18");
}

:global(.g3likac1n) {
  d: path("M6 19L6 6M1.7071 10.2929L6 6L10.2929 10.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

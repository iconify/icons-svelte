<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yopdcqsuw"/><path class="g3likac1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-wide-narrow-sharp-duotone" {...props}></Icon>
<style>
:global(.g3likac1n) {
  d: path("M6 19L6 6M1.7071 10.2929L6 6L10.2929 10.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yopdcqsuw) {
  stroke-opacity: 0.4;
  d: path("M13 6L23 6M13 10L21 10M13 14L19 14M13 18L17 18");
}

</style>

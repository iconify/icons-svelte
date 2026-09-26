<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rimwulb6m"/><path class="d2wv40upu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-left-sharp-two-tone" {...props}></Icon>
<style>
:global(.d2wv40upu) {
  d: path("M4 1L4 9");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rimwulb6m) {
  stroke-opacity: 0.4;
  d: path("M12 1L12 21M20 9L20 23");
}

</style>

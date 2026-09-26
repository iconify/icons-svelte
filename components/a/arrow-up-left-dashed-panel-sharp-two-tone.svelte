<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c-zhdyyrj"/><path class="mch4hbfwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-left-dashed-panel-sharp-two-tone" {...props}></Icon>
<style>
:global(.c-zhdyyrj) {
  stroke-opacity: 0.4;
  d: path("M9.5 21L14.5 21M21 14.5L21 9.5M3 16L3 21L7 21M17 21L21 21L21 17M16 3L21 3L21 7");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.mch4hbfwc) {
  d: path("M12.7929 12.7929L3.1464 3.1464M3 13.5L3 3L13.5 3");
}

</style>

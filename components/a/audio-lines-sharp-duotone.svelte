<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gx0xjxlxa"/><path class="bfgkgvs1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-sharp-duotone" {...props}></Icon>
<style>
:global(.bfgkgvs1u) {
  d: path("M4 9L4 15M12 2L12 22M20 9L20 15");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.gx0xjxlxa) {
  stroke-opacity: 0.4;
  d: path("M8 5L8 19M16 6L16 18");
}

</style>

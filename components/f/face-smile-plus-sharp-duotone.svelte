<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u2rpwubdb"/><path class="ntq22w6oh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:face-smile-plus-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ntq22w6oh) {
  d: path("M19 1L19 9M15 5L23 5");
}

:global(.u2rpwubdb) {
  stroke-opacity: 0.4;
  d: path("M22 11L22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2L13 2M9 9L9 12M15 9L15 12M8.7071 14.7071L9 15C10 16 11 16.5 12 16.5C13 16.5 14 16 15 15L15.2929 14.7071");
}

</style>

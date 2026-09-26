<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kqaeisbkg"/><path class="bg_rw5b8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-sharp-fill" {...props}></Icon>
<style>
:global(.bg_rw5b8q) {
  d: path("M10 12L23 12M17 12L17 17M21 12L21 17");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kqaeisbkg) {
  fill: currentColor;
  d: path("M11 12C11 14.7614 8.7614 17 6 17C3.2386 17 1 14.7614 1 12C1 9.2386 3.2386 7 6 7C8.7614 7 11 9.2386 11 12Z");
  stroke: none;
}

</style>

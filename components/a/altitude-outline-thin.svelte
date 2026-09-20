<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nh1hchbhr"/><path class="tp19rhqzz"/><path class="gcbumkb_o"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:altitude-outline-thin" {...props}></Icon>
<style>
:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.gcbumkb_o) {
  d: path("M16.5 5.5 19 3l2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nh1hchbhr) {
  d: path("m3 18 7 -7 7 7");
}

:global(.tp19rhqzz) {
  d: path("M19 3v15");
}

</style>

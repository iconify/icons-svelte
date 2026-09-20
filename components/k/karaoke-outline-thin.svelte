<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ihqwt60-f"/><path class="v0y09obth"/><path class="hclo6jb2r"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:karaoke-outline-thin" {...props}></Icon>
<style>
:global(.hclo6jb2r) {
  d: path("M8 16h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ihqwt60-f) {
  d: path("M9 6a3 3 0 0 1 3 -3 3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3 3 3 0 0 1 -3 -3Z");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.v0y09obth) {
  d: path("M12 12v4");
}

</style>

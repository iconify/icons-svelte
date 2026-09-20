<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="co4ft5twa"/><path class="f8gsx7b5s"/><path class="h552nsb3x"/><path class="c0kdmnbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kayak-outline-regular" {...props}></Icon>
<style>
:global(.c0kdmnbne) {
  d: path("M21 5h-3v6h3Z");
}

:global(.co4ft5twa) {
  d: path("M3 15c4 -2 14 -2 18 0 -4 5 -14 5 -18 0");
}

:global(.f8gsx7b5s) {
  d: path("M6 8h12");
}

:global(.h552nsb3x) {
  d: path("M3 5h3v6H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

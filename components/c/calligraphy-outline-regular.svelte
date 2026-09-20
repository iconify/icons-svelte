<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mqs1sybxa"/><path class="ykenr4b4h"/><path class="y1sgy9_rm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calligraphy-outline-regular" {...props}></Icon>
<style>
:global(.mqs1sybxa) {
  d: path("m13 3 4 4 -7 7 -4 -4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y1sgy9_rm) {
  d: path("M13 20c3 -2 6 -2 8 0");
}

:global(.ykenr4b4h) {
  d: path("m8 12 -4 4v4h4l4 -4");
}

</style>

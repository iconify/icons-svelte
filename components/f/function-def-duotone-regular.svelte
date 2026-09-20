<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f5-0n-bni"/><path class="ddxf7pboj"/><path class="y8piwob-e"/><path class="dxtd0mgej"/><path class="a8ca2rpxt"/><path class="y0y0ccsoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:function-def-duotone-regular" {...props}></Icon>
<style>
:global(.a8ca2rpxt) {
  d: path("M15 5h3v14h-3");
}

:global(.ddxf7pboj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 5h3v14h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dxtd0mgej) {
  d: path("M9 5H6v14h3");
}

:global(.f5-0n-bni) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 5H6v14h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.y8piwob-e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

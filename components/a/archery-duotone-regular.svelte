<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pwnjwxbqo"/><path class="is4gb6hvz"/><path class="xl0-albli"/><path class="gmcwnnbyg"/><path class="ndk47rb8x"/><path class="wuvisubmw"/><path class="em798y7rn"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:archery-duotone-regular" {...props}></Icon>
<style>
:global(.em798y7rn) {
  d: path("M6 12h14");
}

:global(.gmcwnnbyg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.is4gb6hvz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.ndk47rb8x) {
  d: path("M8 3c6 3 6 15 0 18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pwnjwxbqo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3c6 3 6 15 0 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.xl0-albli) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

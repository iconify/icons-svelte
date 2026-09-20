<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="umkaotb6q"/><path class="aqrf9ebcv"/><path class="wmthecefb"/><path class="w_x_r3bqv"/><path class="mvvbl7zxc"/><path class="vhnbtvbtn"/><path class="spg3og_ww"/><path class="f6kbfx-8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-bin-duotone-regular" {...props}></Icon>
<style>
:global(.aqrf9ebcv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f6kbfx-8d) {
  d: path("m9 17 3 -3 3 3");
}

:global(.mvvbl7zxc) {
  d: path("M6 8v13h12V8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.spg3og_ww) {
  d: path("M9 8V5h6v3");
}

:global(.umkaotb6q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8v13h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.w_x_r3bqv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 17 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wmthecefb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 8V5h6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

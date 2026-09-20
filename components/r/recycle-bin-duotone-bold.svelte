<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="evva1ccpa"/><path class="nu0ti3ggl"/><path class="dh1ppiw4w"/><path class="qa-ce_2ax"/><path class="mvvbl7zxc"/><path class="vhnbtvbtn"/><path class="spg3og_ww"/><path class="f6kbfx-8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-bin-duotone-bold" {...props}></Icon>
<style>
:global(.dh1ppiw4w) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8V5h6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.evva1ccpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 8v13h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f6kbfx-8d) {
  d: path("m9 17 3 -3 3 3");
}

:global(.mvvbl7zxc) {
  d: path("M6 8v13h12V8");
}

:global(.nu0ti3ggl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qa-ce_2ax) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 17 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.spg3og_ww) {
  d: path("M9 8V5h6v3");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>

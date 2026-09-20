<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zl00uacsv"/><path class="s9jzbjbwv"/><path class="a5bxscc_o"/><path class="ep4j44bia"/><path class="mvvbl7zxc"/><path class="vhnbtvbtn"/><path class="spg3og_ww"/><path class="f6kbfx-8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-bin-duotone-thin" {...props}></Icon>
<style>
:global(.a5bxscc_o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8V5h6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ep4j44bia) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 17 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f6kbfx-8d) {
  d: path("m9 17 3 -3 3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mvvbl7zxc) {
  d: path("M6 8v13h12V8");
}

:global(.s9jzbjbwv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.spg3og_ww) {
  d: path("M9 8V5h6v3");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.zl00uacsv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v13h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

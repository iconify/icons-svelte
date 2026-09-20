<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kh3dhlbde"/><path class="zr-n-ubjz"/><path class="edg0x3nuq"/><path class="wvha8hh3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:close-duotone-thin" {...props}></Icon>
<style>
:global(.edg0x3nuq) {
  d: path("m5 5 14 14");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kh3dhlbde) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 5 14 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wvha8hh3o) {
  d: path("M19 5 5 19");
}

:global(.zr-n-ubjz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 5 5 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

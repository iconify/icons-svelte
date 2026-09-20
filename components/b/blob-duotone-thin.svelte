<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xraocd5qw"/><path class="mm5qhtb0x"/><path class="el753yuux"/><path class="fb4zxqney"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blob-duotone-thin" {...props}></Icon>
<style>
:global(.el753yuux) {
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.fb4zxqney) {
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mm5qhtb0x) {
  fill: currentColor;
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xraocd5qw) {
  fill: currentColor;
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

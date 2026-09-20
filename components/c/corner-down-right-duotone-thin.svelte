<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9lzy9btx"/><path class="bmpppjasm"/><path class="isvgtub8p"/><path class="xpi-ctm3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-down-right-duotone-thin" {...props}></Icon>
<style>
:global(.bmpppjasm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 9 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.isvgtub8p) {
  d: path("M4 4v10h16");
}

:global(.s9lzy9btx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v10h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xpi-ctm3k) {
  d: path("m15 9 5 5 -5 5");
}

</style>

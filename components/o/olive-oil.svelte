<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="za-8hgbdf"/><circle class="mlqk6dbfd"/><path class="ovsex995p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:olive-oil" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mlqk6dbfd) {
  cx: 18px;
  cy: 18px;
  r: 2.75px;
}

:global(.ovsex995p) {
  d: path("M18 15.25q0-2.25 2.25-3");
}

:global(.za-8hgbdf) {
  d: path("M8.25 2.75h3.5v3.5l2 2.75v10.5A1.75 1.75 0 0 1 12 21.25H8a1.75 1.75 0 0 1-1.75-1.75V9l2-2.75Zm0 2.25h3.5");
}

</style>

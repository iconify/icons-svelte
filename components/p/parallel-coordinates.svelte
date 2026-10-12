<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="myvl9cblf"/><path class="ogabaqb3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parallel-coordinates" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.myvl9cblf) {
  d: path("M4 4v16m8-16v16m8-16v16M4 7l8 8l8-6");
}

:global(.ogabaqb3s) {
  d: path("m4 16l8-9l8 8");
}

</style>

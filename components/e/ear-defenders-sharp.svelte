<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zdy7-611b"/><path class="ohcjvuwxz"/><path class="xt51qgbyr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ear-defenders-sharp" {...props}></Icon>
<style>
:global(.ohcjvuwxz) {
  d: path("M4.25 10.8a7.75 7.75 0 0 1 15.5 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xt51qgbyr) {
  d: path("M7.25 10.8a4.75 4.75 0 0 1 9.5 0");
}

:global(.zdy7-611b) {
  d: path("M2.75 10.5h5.5v10.75h-5.5zm13 0h5.5v10.75h-5.5z");
}

</style>

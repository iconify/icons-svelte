<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l5g864bjc"/><path class="f-b0yfbli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:light-switch-sharp" {...props}></Icon>
<style>
:global(.f-b0yfbli) {
  d: path("M9.5 6.75h5v10.5h-5zm0 5.25h5");
}

:global(.l5g864bjc) {
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

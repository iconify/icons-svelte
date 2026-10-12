<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zs1nyzxkz"/><path class="ufwe11b4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:day-view-sharp" {...props}></Icon>
<style>
:global(.ufwe11b4k) {
  d: path("M11.25 11.25h6.5V16h-6.5z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zs1nyzxkz) {
  d: path("M3.25 3.25h17.5v17.5H3.25zm0 5h17.5M6 12h2m-2 3h2m-2 3h2");
}

</style>

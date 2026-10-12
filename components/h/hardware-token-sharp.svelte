<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hdt6cdccd"/><path class="b0qn-9bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hardware-token-sharp" {...props}></Icon>
<style>
:global(.b0qn-9bho) {
  d: path("M9.25 9.25h9.5v5.5h-9.5zm2 2.75h1.25m2.75 0h1.25");
}

:global(.hdt6cdccd) {
  d: path("M6.5 6.75h14.75v10.5H6.5zm0 2.69a2.75 2.75 0 1 0 0 5.12");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

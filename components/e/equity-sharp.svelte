<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e5-3wqbcf"/><path class="t-cts4bra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:equity-sharp" {...props}></Icon>
<style>
:global(.e5-3wqbcf) {
  d: path("M2.75 4.75h18.5v14.5H2.75zM6.25 9h3m-3 3h3m-3 3h3");
}

:global(.t-cts4bra) {
  d: path("M15.25 9a3 3 0 1 0 3 3h-3Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

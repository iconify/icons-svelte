<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u-gkr4b6f"/><path class="he1evqb6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pie-slice-sharp" {...props}></Icon>
<style>
:global(.he1evqb6c) {
  d: path("M8.75 6.82a7 7 0 1 0 7.93 7.93");
}

:global(.u-gkr4b6f) {
  d: path("M12 11.5V2.75a8.75 8.75 0 0 1 8.75 8.75Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

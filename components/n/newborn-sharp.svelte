<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rr-nm9b_q"/><circle class="argn9bbqd"/><path class="ktnabfbml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:newborn-sharp" {...props}></Icon>
<style>
:global(.argn9bbqd) {
  cx: 12px;
  cy: 8.25px;
  r: 2.75px;
}

:global(.ktnabfbml) {
  d: path("m6.75 13.5l10.5 3.5");
}

:global(.rr-nm9b_q) {
  d: path("M6.75 3h10.5v18.25H6.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

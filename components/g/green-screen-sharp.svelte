<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mx296muuh"/><circle class="r-vnokzof"/><path class="xes36ab-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:green-screen-sharp" {...props}></Icon>
<style>
:global(.mx296muuh) {
  d: path("M2.75 2.75h18.5v14H2.75z");
}

:global(.r-vnokzof) {
  cx: 12px;
  cy: 7.5px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xes36ab-a) {
  d: path("M7.5 16.75a4.5 4.5 0 0 1 9 0Zm-2.75 0l-1.25 4.5m15.75-4.5l1.25 4.5");
}

</style>

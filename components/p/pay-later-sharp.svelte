<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dmfpm2rbl"/><circle class="upu83lbfh"/><path class="kwt9vubhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pay-later-sharp" {...props}></Icon>
<style>
:global(.dmfpm2rbl) {
  d: path("M11.75 18.75h-9V5.25h18.5v6m-18.5-2h18.5");
}

:global(.kwt9vubhj) {
  d: path("M17 14.75V17h2");
}

:global(.upu83lbfh) {
  cx: 17px;
  cy: 17px;
  r: 4.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

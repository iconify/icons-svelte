<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="klcrqdbde"/><circle class="upu83lbfh"/><path class="lj9r6l14u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:meeting-minutes-sharp" {...props}></Icon>
<style>
:global(.klcrqdbde) {
  d: path("M9.75 21.25h-5.5V2.75h13v7M7.5 7H14m-6.5 3.5H14M7.5 14h3");
}

:global(.lj9r6l14u) {
  d: path("M17 15v2l1.25.75");
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

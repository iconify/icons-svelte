<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="c5_xrjbae"/><circle class="e3ijufb_j"/><circle class="dmb4gdc-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:auto-rickshaw-sharp" {...props}></Icon>
<style>
:global(.c5_xrjbae) {
  d: path("M20.5 14.5V4.25h-13l-.75 2l-1.25 4H3.25v4.25Z");
}

:global(.dmb4gdc-s) {
  cx: 17.5px;
  cy: 19.25px;
  r: 1.75px;
}

:global(.e3ijufb_j) {
  cx: 5.5px;
  cy: 19.25px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

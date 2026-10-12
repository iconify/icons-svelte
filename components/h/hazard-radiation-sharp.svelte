<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y1g8afaup"/><circle class="peiq2hfxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hazard-radiation-sharp" {...props}></Icon>
<style>
:global(.peiq2hfxm) {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1g8afaup) {
  d: path("M7 12H2.75a9.25 9.25 0 0 1 4.63-8.01L9.5 7.67A5 5 0 0 0 7 12Zm7.5-4.33l2.13-3.68A9.25 9.25 0 0 1 21.25 12H17a5 5 0 0 0-2.5-4.33Zm0 8.66l2.13 3.68a9.25 9.25 0 0 1-9.25 0l2.12-3.68a5 5 0 0 0 5 0Z");
}

</style>

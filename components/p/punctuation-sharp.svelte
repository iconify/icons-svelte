<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zc07nibya"/><circle class="l78ls8mni"/><circle class="frsmk1b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:punctuation-sharp" {...props}></Icon>
<style>
:global(.frsmk1b8c) {
  cx: 17px;
  cy: 19px;
  r: 1.25px;
}

:global(.l78ls8mni) {
  cx: 7.5px;
  cy: 19px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zc07nibya) {
  d: path("M3.75 7.5a3.75 3.75 0 1 1 5.8 3.15L7.5 12.017v2.733m9.5-11v11");
}

</style>

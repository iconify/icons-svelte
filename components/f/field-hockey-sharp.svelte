<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rfz_djb8q"/><circle class="jhtbhmnge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:field-hockey-sharp" {...props}></Icon>
<style>
:global(.jhtbhmnge) {
  cx: 17px;
  cy: 18.5px;
  r: 2.25px;
}

:global(.rfz_djb8q) {
  d: path("m17.25 2.75l-8 14.5a2.75 2.75 0 0 1-5-2.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

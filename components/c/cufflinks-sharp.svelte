<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jc6oap-gd"/><circle class="dx6qgibjz"/><path class="humz-r42z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cufflinks-sharp" {...props}></Icon>
<style>
:global(.dx6qgibjz) {
  cx: 17.5px;
  cy: 8.5px;
  r: 3.75px;
}

:global(.humz-r42z) {
  d: path("M6.5 12.25v5.25m11-5.25v5.25m-13.75 0h5.5V20h-5.5zm11 0h5.5V20h-5.5z");
}

:global(.jc6oap-gd) {
  cx: 6.5px;
  cy: 8.5px;
  r: 3.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

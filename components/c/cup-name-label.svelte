<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="etq9du57q"/><path class="dbvhpcc_p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cup-name-label" {...props}></Icon>
<style>
:global(.dbvhpcc_p) {
  d: path("M9 10h6v5H9Z");
}

:global(.etq9du57q) {
  d: path("M4 3h16v3.5H4Zm1 3.5L7 21h10l2-14.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

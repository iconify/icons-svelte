<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2l5lbczz"/><path class="pli5nub9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coal-pile" {...props}></Icon>
<style>
:global(.d2l5lbczz) {
  d: path("M2.5 17h19M4 17l2-4l2.5-1.5l1.5-3L13 7l2.5 2l2 2l1 2.5L20 17");
}

:global(.pli5nub9h) {
  d: path("m8.5 11.5l4 1l3-3.5m-3 3.5L12 17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

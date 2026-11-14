<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="femaqu8cj"/><path class="l9corfx1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrival-route" {...props}></Icon>
<style>
:global(.femaqu8cj) {
  d: path("M3 3a14.5 14.5 0 0 1 3.75.5m2.75 1a14.5 14.5 0 0 1 3.25 2.25m2 2.25a14.5 14.5 0 0 1 1.75 3.25m.75 3a14.5 14.5 0 0 1 .25 2.25");
}

:global(.l9corfx1v) {
  d: path("m15 15l2.5 2.5L20 15m-7.5 6h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

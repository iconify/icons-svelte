<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hg5w1c0qd"/><path class="ct6hs4bph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:antimatter" {...props}></Icon>
<style>
:global(.ct6hs4bph) {
  d: path("M13.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.hg5w1c0qd) {
  fill: currentColor;
  d: path("M2.5 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

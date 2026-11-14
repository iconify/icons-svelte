<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vmk4jiblp"/><path class="r1etmvb3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cardio-heart" {...props}></Icon>
<style>
:global(.r1etmvb3l) {
  d: path("M6 12h3l1.5-2.5L13 15l1.5-3H18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vmk4jiblp) {
  d: path("M12 20c-5-3.5-9.5-7-9.5-11.25c0-3 2.25-5 4.75-5c2 0 3.75 1 4.75 2.75c1-1.75 2.75-2.75 4.75-2.75c2.5 0 4.75 2 4.75 5C21.5 13 17 16.5 12 20Z");
}

</style>

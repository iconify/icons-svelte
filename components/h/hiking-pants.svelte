<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1_er-brp"/><path class="iwsy61scj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hiking-pants" {...props}></Icon>
<style>
:global(.iwsy61scj) {
  d: path("M14.5 2.5q.25 4.5 4 5.5");
}

:global(.k1_er-brp) {
  d: path("M6 2.5h12l1.5 19H14L12 9l-2 12.5H4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjpx8jbnb"/><path class="acqbm5b-u"/><path class="lyqyhsbxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:earlobe" {...props}></Icon>
<style>
:global(.acqbm5b-u) {
  fill: currentColor;
  d: path("M15.5 16c-.25 3.25-2.25 5-4.5 5c-1.75 0-3-1-3.5-2.5c2.5 0 5.5-.5 8-2.5Z");
}

:global(.hjpx8jbnb) {
  d: path("M6 9.5a6.5 6.5 0 0 1 13 0c0 3.5-3 4.5-3.5 6.5");
}

:global(.lyqyhsbxk) {
  d: path("M9.5 9.5a3 3 0 0 1 6 0c0 1.75-1.75 2.25-2.25 4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

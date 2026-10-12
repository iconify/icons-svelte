<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lt5cnnoly"/><path class="cmyms_bhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-spiral-sharp" {...props}></Icon>
<style>
:global(.cmyms_bhp) {
  d: path("M14 10.75L17.25 14l3.25-3.25");
}

:global(.lt5cnnoly) {
  d: path("M9.25 12.5a2 2 0 0 1 4 0a4 4 0 0 1-8 0a6 6 0 0 1 12 0V14");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

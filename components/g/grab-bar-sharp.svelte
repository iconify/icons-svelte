<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v-nshmb6z"/><circle class="eaczzeban"/><path class="k6czokdum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:grab-bar-sharp" {...props}></Icon>
<style>
:global(.eaczzeban) {
  cx: 19px;
  cy: 6.5px;
  r: 2.25px;
}

:global(.k6czokdum) {
  d: path("M5 8.75v6.5h14v-6.5M2.75 21.25h18.5");
}

:global(.v-nshmb6z) {
  cx: 5px;
  cy: 6.5px;
  r: 2.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

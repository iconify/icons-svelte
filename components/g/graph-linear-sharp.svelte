<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b5_b17dsl"/><path class="gnymwcb8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:graph-linear-sharp" {...props}></Icon>
<style>
:global(.b5_b17dsl) {
  d: path("M4.75 2.75v18.5h16.5");
}

:global(.gnymwcb8y) {
  d: path("M8.5 16.25c1.75-9.75 4.25-9.75 5.75-5s3.5 5.25 6.5-5.25");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

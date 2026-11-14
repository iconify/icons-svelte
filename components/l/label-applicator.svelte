<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ob4y0-yxf"/><path class="eextsptkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:label-applicator" {...props}></Icon>
<style>
:global(.eextsptkd) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v4.8m0 3.4v1.8M7.5 4.75l9 4.5M14.25 18l2.5-2.75h5v5.5h-5ZM17 18h.01");
}

:global(.ob4y0-yxf) {
  d: path("M13.095 20.952L12 21.5L3 17V7l9-4.5L21 7v5.438");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

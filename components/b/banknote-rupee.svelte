<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ch0hk1f6s"/><path class="h2l6qpb2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:banknote-rupee" {...props}></Icon>
<style>
:global(.ch0hk1f6s) {
  d: path("M2.5 4.5h19v15h-19Zm6.25 3h6.5M8.75 10h6.5");
}

:global(.h2l6qpb2n) {
  d: path("M10.75 7.5c1.6 0 2.45 1 2.5 2.5c-.05 1.3-.9 2.3-2.5 2.25h-2l5 4.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

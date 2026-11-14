<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b888nub2v"/><path class="c096n9bvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newsletter-issue" {...props}></Icon>
<style>
:global(.b888nub2v) {
  d: path("M3.5 2.5h15v19h-15Z");
}

:global(.c096n9bvu) {
  d: path("m7 6l4 3l4-3m-8 6.5h8m-8 4h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

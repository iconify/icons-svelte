<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="ubr3mw63z"/><path class="jel1nl2tj"/><path class="nh1i2bbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-highlight" {...props}></Icon>
<style>
:global(.jel1nl2tj) {
  fill: currentColor;
  d: path("M7.5 11h7v3h-7Zm7 0l2 1.5l-2 1.5Z");
}

:global(.nh1i2bbzg) {
  d: path("M8 18h6");
}

:global(.ubr3mw63z) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M8 6.5h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uwivq1yig) {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

</style>

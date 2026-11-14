<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x7u63pbeu"/><path class="jf4uqjblp"/><path class="r-n-w1cgt"/><path class="cx6dow2ci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:canned-fruit" {...props}></Icon>
<style>
:global(.cx6dow2ci) {
  d: path("M12 11q-1.5 2.5-.5 5m.5-5q1.25-1.75 3-1q-1.25 1.75-3 1Z");
}

:global(.jf4uqjblp) {
  d: path("M5 5v14a7 2 0 0 0 14 0V5");
}

:global(.r-n-w1cgt) {
  d: path("M8.5 14.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x7u63pbeu) {
  d: path("M5 5a7 2 0 1 0 14 0A7 2 0 1 0 5 5Z");
}

</style>

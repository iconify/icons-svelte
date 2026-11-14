<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nnlgb5bfs"/><path class="uvf3q3b2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hockey-referee" {...props}></Icon>
<style>
:global(.nnlgb5bfs) {
  d: path("M9 10h11.5v3.5h-6.75A5 5 0 1 1 9 10Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uvf3q3b2b) {
  d: path("M7.25 10.25C4.5 5.5 6 2.5 9.5 2.5s5 3 3 7.5M9 15h.01");
}

</style>

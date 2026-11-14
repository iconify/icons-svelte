<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k0v1t97jg"/><path class="n_wsqz5bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mine-flooding" {...props}></Icon>
<style>
:global(.k0v1t97jg) {
  d: path("M3 21.5V11a9 9 0 0 1 18 0v10.5");
}

:global(.n_wsqz5bh) {
  d: path("M6 13.5q1.5-1.5 3 0t3 0t3 0t3 0m-12 5q1.5-1.5 3 0t3 0t3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

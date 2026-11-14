<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vc1h42-ij"/><path class="nzyov2b1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rip-current" {...props}></Icon>
<style>
:global(.nzyov2b1h) {
  d: path("m9 7l3-3l3 3M2.5 10.5q1.5-1.5 3 0t3 0m7 0q1.5-1.5 3 0t3 0m-19 5q1.5-1.5 3 0t3 0m7 0q1.5-1.5 3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vc1h42-ij) {
  d: path("M12 21c0-6-1-11 0-17");
}

</style>

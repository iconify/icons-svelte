<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xl8wcug9u"/><path class="dqgg4cz2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crater-lake" {...props}></Icon>
<style>
:global(.dqgg4cz2h) {
  d: path("M9.5 11.5q1.25-1.25 2.5 0t2.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xl8wcug9u) {
  d: path("M2.5 20L9 6h6l6.5 14Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pe5s6dbpq"/><path class="s5bxd_b6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pool-wave-machine" {...props}></Icon>
<style>
:global(.pe5s6dbpq) {
  d: path("M2.5 4v13.5A2.5 2.5 0 0 0 5 20h14a2.5 2.5 0 0 0 2.5-2.5V4");
}

:global(.s5bxd_b6u) {
  d: path("M6 7.5q1.5-1.25 3 0t3 0t3 0t3 0M6 12q1.5-1.25 3 0t3 0t3 0t3 0M6 16.5q1.5-1.25 3 0t3 0t3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

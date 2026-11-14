<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pscjkuumj"/><path class="r1ynu1bqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-ball-washer" {...props}></Icon>
<style>
:global(.pscjkuumj) {
  d: path("M7.5 14a6 6 0 1 1 9 0");
}

:global(.r1ynu1bqr) {
  d: path("M3 14q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M3 18.5q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0M12 7h.01m-2.26 3h.01m4.49 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

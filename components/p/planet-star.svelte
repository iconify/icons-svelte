<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="srupzfspc"/><path class="k7n1ib9wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:planet-star" {...props}></Icon>
<style>
:global(.k7n1ib9wx) {
  d: path("M6 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM18.5 2q.75 2.75 3.5 3.5q-2.75.75-3.5 3.5q-.75-2.75-3.5-3.5q2.75-.75 3.5-3.5Z");
}

:global(.srupzfspc) {
  d: path("M2 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

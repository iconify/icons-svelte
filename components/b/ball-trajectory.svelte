<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9omytbzv"/><path class="j17mt-bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ball-trajectory" {...props}></Icon>
<style>
:global(.i9omytbzv) {
  d: path("M11 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

:global(.j17mt-bad) {
  d: path("M13 4q2 4 0 8m6-8q-2 4 0 8M2.5 21q1.5-8 6-9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

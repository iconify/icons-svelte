<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3x6pq0mc"/><path class="xx1tbu30f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roundabout-cw-exit-right" {...props}></Icon>
<style>
:global(.e3x6pq0mc) {
  d: path("M10 21.5v-5a5.5 5.5 0 1 1 5.5-5.5h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xx1tbu30f) {
  d: path("M18.25 8.75L20.5 11l-2.25 2.25M10 16.5a5.5 5.5 0 0 0 5.5-5.5M8 3.5l2 2l-2 2");
}

</style>

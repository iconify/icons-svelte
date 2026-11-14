<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mu7dsh2wi"/><path class="rhh_egbxt"/><path class="id1aw0lsj"/><path class="ip7n5cctz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dialogue-flow" {...props}></Icon>
<style>
:global(.id1aw0lsj) {
  d: path("M9.5 12.5h9V7.75");
}

:global(.ip7n5cctz) {
  d: path("M16.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.mu7dsh2wi) {
  d: path("M4.5 2.5h6a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-4l-2.5 2v-2a2 2 0 0 1-1.5-2v-3a2 2 0 0 1 2-2Zm10 12.75h5a2 2 0 0 1 2 2v4.25L19 20h-4.5a2 2 0 0 1-2-2v-.75a2 2 0 0 1 2-2Z");
}

:global(.rhh_egbxt) {
  d: path("M9.5 9.5v8h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

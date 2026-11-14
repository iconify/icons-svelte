<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gc40fjwbk"/><path class="ps5al2r6a"/><path class="o5v09ccth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:database-compare" {...props}></Icon>
<style>
:global(.gc40fjwbk) {
  d: path("M2.5 5a4 1.75 0 1 0 8 0a4 1.75 0 1 0-8 0Z");
}

:global(.o5v09ccth) {
  d: path("M13.5 5v8a4 1.75 0 0 0 8 0V5M4 19.5h16m-14-2l-2 2l2 2m12-4l2 2l-2 2");
}

:global(.ps5al2r6a) {
  d: path("M2.5 5v8a4 1.75 0 0 0 8 0V5m3 0a4 1.75 0 1 0 8 0a4 1.75 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

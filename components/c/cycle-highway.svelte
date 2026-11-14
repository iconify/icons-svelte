<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i0grsesdq"/><path class="y6voxlbco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cycle-highway" {...props}></Icon>
<style>
:global(.i0grsesdq) {
  d: path("m2 21.5l5-19m15 19l-5-19M6 17.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm6.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y6voxlbco) {
  d: path("M8.75 17.25h3.5l2.5-5m.5 5l-1.5-6.75h2m-5.25 2.25l1.75 4.5m-2.75-4.5h2.25");
}

</style>

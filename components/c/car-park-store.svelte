<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m4rmrt_ay"/><path class="ef_suabze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:car-park-store" {...props}></Icon>
<style>
:global(.ef_suabze) {
  d: path("M7.5 19.5v-7h4v7m4.5 2v-7h2.75a2.25 2.25 0 0 1 0 4.5H16");
}

:global(.m4rmrt_ay) {
  d: path("M3 3h16v4H3Zm1 4v12.5h9.2m4.8-7.8V7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

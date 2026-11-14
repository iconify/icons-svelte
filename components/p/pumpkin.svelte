<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yni-3-bqd"/><path class="qnr1gfunj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pumpkin" {...props}></Icon>
<style>
:global(.qnr1gfunj) {
  d: path("M12 7c0-2 .5-3 2-3.5M12 7c-3 3-3 10 0 13m0-13c3 3 3 10 0 13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yni-3-bqd) {
  d: path("M12 7c-7-.5-9 4-8.5 7.5S7.5 20 12 20s8-2 8.5-5.5S19 6.5 12 7Z");
}

</style>

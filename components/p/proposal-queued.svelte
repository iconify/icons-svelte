<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r90gm2bub"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:proposal-queued" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.r90gm2bub) {
  d: path("M12.1 19.5H3v-17h13.5v9.6M6.5 7H13m-6.5 4H11m3.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

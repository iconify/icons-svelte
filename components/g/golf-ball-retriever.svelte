<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t_4plbt9w"/><path class="mtmm_2bga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-ball-retriever" {...props}></Icon>
<style>
:global(.mtmm_2bga) {
  d: path("M4.5 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.t_4plbt9w) {
  d: path("M11.75 11.75L21 21M11.743 3.257a6 6 0 0 1-8.486 8.486");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

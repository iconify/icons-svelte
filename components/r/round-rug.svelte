<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r2cx5_i_e"/><path class="s1avswkyi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:round-rug" {...props}></Icon>
<style>
:global(.r2cx5_i_e) {
  d: path("M2.5 12a9.5 6.5 0 1 0 19 0a9.5 6.5 0 1 0-19 0Z");
}

:global(.s1avswkyi) {
  d: path("M6 12a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

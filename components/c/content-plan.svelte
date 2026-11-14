<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vp3_m3b5w"/><path class="qyvttacaf"/><path class="seqns1bli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:content-plan" {...props}></Icon>
<style>
:global(.qyvttacaf) {
  d: path("M14 2.5v5h5m-11 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.seqns1bli) {
  d: path("M9.5 13v4H13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vp3_m3b5w) {
  d: path("M14 2.5H7a2 2 0 0 0-2 2v15a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-12Z");
}

</style>

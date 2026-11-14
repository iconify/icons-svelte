<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_19yjbwc"/><path class="j2iwrcc2y"/><path class="dt-ex-t_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rag-status" {...props}></Icon>
<style>
:global(.dt-ex-t_o) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 5.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.e_19yjbwc) {
  d: path("M7 2h10v20H7Z");
}

:global(.j2iwrcc2y) {
  fill: currentColor;
  d: path("M10 6.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_j19dzst"/><path class="xmyir0cuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:counting-fingers" {...props}></Icon>
<style>
:global(.s_j19dzst) {
  d: path("M7 15V6.25a1.75 1.75 0 0 1 3.5 0V11V4.25a1.75 1.75 0 0 1 3.5 0V11V6.25a1.75 1.75 0 0 1 3.5 0V15c0 4-2.25 6.5-5.5 6.5S7 19 7 15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xmyir0cuh) {
  d: path("M7 14c3-.25 5.75.5 6.75 2.5");
}

</style>

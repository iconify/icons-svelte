<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j-uy7bc_e"/><path class="gq05hacof"/><path class="zu_yktbwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:massage-hands" {...props}></Icon>
<style>
:global(.gq05hacof) {
  d: path("M6 11a6 2.75 0 1 0 12 0a6 2.75 0 1 0-12 0Z");
}

:global(.j-uy7bc_e) {
  d: path("M4 17.25a8 3.5 0 1 0 16 0a8 3.5 0 1 0-16 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zu_yktbwk) {
  d: path("M8.25 5.75a3.75 2.5 0 1 0 7.5 0a3.75 2.5 0 1 0-7.5 0Z");
}

</style>

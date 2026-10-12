<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rak2be21z"/><path class="k-nxuebzu"/><path class="c5xa57-du"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dragon" {...props}></Icon>
<style>
:global(.c5xa57-du) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 8.5h.01");
}

:global(.k-nxuebzu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 7.4C9.5 5.5 8 4 5.5 3.25c3 0 5.5 1 7.25 3Z");
}

:global(.rak2be21z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 21.25l1-2.75l-1.75-1.25L6 16l-1.5-2L7 13l-.75-2.25l2.25-.5C9.5 7.5 11.5 6 14 6l5.5 1.25q1.75.5 1.5 2l-.25 1l-5.25.5l3.75 1.5q.75 1.25-.5 1.5L14.5 14c-1.5 1.5-2 4-1.75 7.25Z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

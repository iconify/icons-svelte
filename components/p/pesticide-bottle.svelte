<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y1xvo62vd"/><path class="eybvgdb7z"/><path class="hhnxadcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pesticide-bottle" {...props}></Icon>
<style>
:global(.eybvgdb7z) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.25H13v2.5l2.5 2.5v8.25a1.75 1.75 0 0 1-1.75 1.75h-5.5A1.75 1.75 0 0 1 6.5 19.5v-8.25l2-2.5Zm1 7.5l3 3m0-3l-3 3");
}

:global(.hhnxadcwk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.75 3.5h.01M20.5 6h.01M19.5 8.5h.01");
}

:global(.y1xvo62vd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3h7.5l2 1.75v1.5h-9.5ZM15 6.25l1.25 2.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

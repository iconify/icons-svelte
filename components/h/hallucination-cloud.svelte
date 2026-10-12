<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jtjgc9yrk"/><path class="trhljirxg"/><path class="r8i1ocbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hallucination-cloud" {...props}></Icon>
<style>
:global(.jtjgc9yrk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 19.6a4 4 0 0 1-.55-7.96a5.75 5.75 0 0 1 10.65-1.39a4.5 4.5 0 0 1-.6 9.35Z");
}

:global(.r8i1ocbvm) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.25h.01");
}

:global(.trhljirxg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12.25a1.75 1.75 0 1 1 2.5 1.6c-.5.25-.75.6-.75 1.15");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

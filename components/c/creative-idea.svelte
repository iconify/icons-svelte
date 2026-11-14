<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9sf4hbas"/><path class="yr7yb-bwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:creative-idea" {...props}></Icon>
<style>
:global(.d9sf4hbas) {
  d: path("M9 17.75v-1.5c-2.5-1.5-4-4-4-6.5a7 7 0 0 1 14 0c0 2.5-1.5 5-4 6.5v1.5ZM9.5 21h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yr7yb-bwk) {
  d: path("m12.442 8.058l.204.49a1.5 1.5 0 0 0 .806.806l.49.204a.479.479 0 0 1 0 .884l-.49.204a1.5 1.5 0 0 0-.806.806l-.204.49a.479.479 0 0 1-.884 0l-.204-.49a1.5 1.5 0 0 0-.806-.806l-.49-.204a.479.479 0 0 1 0-.884l.49-.204a1.5 1.5 0 0 0 .806-.806l.204-.49a.479.479 0 0 1 .884 0");
}

</style>

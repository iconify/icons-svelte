<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v105zmblb"/><path class="r3k61hkwm"/><path class="t06rkwfxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:insomnia-outline-bold" {...props}></Icon>
<style>
:global(.r3k61hkwm) {
  d: path("M20 5v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t06rkwfxk) {
  d: path("M19 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.v105zmblb) {
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
}

</style>

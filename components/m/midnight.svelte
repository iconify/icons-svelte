<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kf8s_phmr"/><path class="kwsh3kbkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:midnight" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kf8s_phmr) {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12M12 6.75V12");
}

:global(.kwsh3kbkk) {
  d: path("M17.5 13.75a2.75 2.75 0 0 0 3.75 3.75a3.75 3.75 0 1 1-3.75-3.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b2r7vmboc"/><path class="ls26jxgdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:councillor" {...props}></Icon>
<style>
:global(.b2r7vmboc) {
  d: path("M8.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m-3.75 15c0-5 3.5-8 7.5-8s7.5 3 7.5 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ls26jxgdg) {
  d: path("M13.25 18.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>

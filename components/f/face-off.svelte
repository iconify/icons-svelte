<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-zm0gbrw"/><path class="fx8cznbxj"/><path class="wy1szv1dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-off" {...props}></Icon>
<style>
:global(.d-zm0gbrw) {
  d: path("M6.5 2.5L17 18h4");
}

:global(.fx8cznbxj) {
  d: path("M17.5 2.5L7 18H3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wy1szv1dk) {
  fill: currentColor;
  d: path("M9.75 19.5a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0");
}

</style>

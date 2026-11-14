<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xfhp10b-c"/><path class="orm9sfpbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-fork" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.orm9sfpbw) {
  d: path("M7.75 6.75L12 11.5l4.25-4.75M12 11.5v5");
}

:global(.xfhp10b-c) {
  d: path("M3.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-6 14a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>

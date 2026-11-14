<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlh6b-b0b"/><path class="que6n3ozv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-branch-delete" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nlh6b-b0b) {
  d: path("M3.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 7v14.5");
}

:global(.que6n3ozv) {
  d: path("M17 7c0 5.5-11 4.5-11 10m9-2l6 6m0-6l-6 6");
}

</style>

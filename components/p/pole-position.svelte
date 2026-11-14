<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z67hl9k8p"/><path class="hr_1bybig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pole-position" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr_1bybig) {
  d: path("M4 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 3.5v6M18 17l2-1.5");
}

:global(.z67hl9k8p) {
  d: path("M2.5 10V7.5L5 7l4-3h3.5l3 3L21 8v2Z");
}

</style>

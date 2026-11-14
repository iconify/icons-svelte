<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="joem8zb5c"/><path class="b_loldbpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:co2-tag" {...props}></Icon>
<style>
:global(.b_loldbpl) {
  d: path("M5.25 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0m7 3.25a1.75 1.75 0 0 1 0-3.5a2.75 2.75 0 0 1 4.5 0a1.75 1.75 0 0 1 0 3.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.joem8zb5c) {
  d: path("M8.5 5h11a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-11l-6-7Z");
}

</style>

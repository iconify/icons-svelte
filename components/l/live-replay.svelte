<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wx95c7tlb"/><path class="u7nj80b6z"/><path class="njvzl5cqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:live-replay" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.njvzl5cqf) {
  d: path("M13.5 7.25L12 8.75l1.5 1.5");
}

:global(.u7nj80b6z) {
  d: path("M12 8.75a3.75 3.75 0 1 1-3.75 3.75");
}

:global(.wx95c7tlb) {
  d: path("M7.75 4.5h8.5a5.25 5.25 0 0 1 5.25 5.25v4.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-4.5A5.25 5.25 0 0 1 7.75 4.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wx95c7tlb"/><path class="j80ql7f1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:optional-value" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j80ql7f1l) {
  d: path("M9.5 9.5a2.5 2.5 0 1 1 3.5 2.25c-.75.25-1 .75-1 1.5M12 16h.01");
}

:global(.wx95c7tlb) {
  d: path("M7.75 4.5h8.5a5.25 5.25 0 0 1 5.25 5.25v4.5a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25v-4.5A5.25 5.25 0 0 1 7.75 4.5");
}

</style>

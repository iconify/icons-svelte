<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tmfrv5gtd"/><path class="hb42dqepe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:disease-mildew" {...props}></Icon>
<style>
:global(.hb42dqepe) {
  d: path("M6.5 9.5q1.75-2 3 0q1.25-2 2.5 0q1.25-2 2.5 0q1.25-2 3 0m-8.25 3.25h.01m5.49 0h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tmfrv5gtd) {
  d: path("M12 2.5c7.5 3.5 8.5 11 0 17c-8.5-6-7.5-13.5 0-17m0 4v15");
}

</style>

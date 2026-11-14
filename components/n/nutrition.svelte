<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y0ro6eb3f"/><path class="ydhp1yo-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nutrition" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0ro6eb3f) {
  d: path("M12 7c-2-1.5-7.5-2-8 4c-.5 5 3 10 5.5 10c1.25 0 1.75-.75 2.5-.75s1.25.75 2.5.75c2.5 0 6-5 5.5-10c-.5-6-6-5.5-8-4m0 0l.75-4.25");
}

:global(.ydhp1yo-w) {
  d: path("M12 9.75c2.25 2 2.25 6 0 8c-2.25-2-2.25-6 0-8m0 2.75h.01M12 15h.01");
}

</style>

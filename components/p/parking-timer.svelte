<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ondbm74wj"/><path class="k4bitbb0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:parking-timer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4bitbb0t) {
  d: path("M10.25 17.5v-8h2.25a2.25 2.25 0 0 1 0 4.5h-2.25");
}

:global(.ondbm74wj) {
  d: path("M4 13.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0m6-11h4m-2 0v3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yl7mf3bbd"/><path class="px7uwxlby"/><path class="bery7-8kf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:database-snapshot" {...props}></Icon>
<style>
:global(.bery7-8kf) {
  d: path("M6.5 12a5.5 2 0 0 0 11 0m-15-4.5V5A2.5 2.5 0 0 1 5 2.5h2.5m9 0H19A2.5 2.5 0 0 1 21.5 5v2.5m0 9V19a2.5 2.5 0 0 1-2.5 2.5h-2.5m-9 0H5A2.5 2.5 0 0 1 2.5 19v-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.px7uwxlby) {
  d: path("M6.5 7.5v9a5.5 2 0 0 0 11 0v-9");
}

:global(.yl7mf3bbd) {
  d: path("M6.5 7.5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="v9flx9bwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:page-snooze-outline-thin" {...props}></Icon>
<style>
:global(.f4yp5uw0u) {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k70w93buq) {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

:global(.v9flx9bwu) {
  d: path("M9.5 9h5l-5 5h5");
}

</style>

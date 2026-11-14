<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6aqm9b5u"/><path class="oh-560cgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:directions-walk" {...props}></Icon>
<style>
:global(.e6aqm9b5u) {
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m.5 4.5l-1.5 6l3 3V21m-3-6.5L8 21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oh-560cgq) {
  d: path("M8 12.5L9.5 9l2.5-.5l2.5 3l2.5 1");
}

</style>

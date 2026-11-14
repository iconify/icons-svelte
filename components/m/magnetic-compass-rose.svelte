<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7qjn6psg"/><path class="azb-kwbyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magnetic-compass-rose" {...props}></Icon>
<style>
:global(.azb-kwbyu) {
  d: path("m13.125 9l.927 2.473a1.5 1.5 0 0 1 0 1.054L13.125 15a1.202 1.202 0 0 1-2.25 0l-.927-2.473a1.5 1.5 0 0 1 0-1.054L10.875 9a1.202 1.202 0 0 1 2.25 0M9.75 12h4.5M6.5 12h.01m10.99 0h.01");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7qjn6psg) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

</style>

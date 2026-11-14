<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vwjnnjbwp"/><path class="m59wu8bxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:marriage-leave" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m59wu8bxs) {
  d: path("M10.5 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0m2.125-9.375l.165.296a1.5 1.5 0 0 1-.091 1.601l-.074.103a.768.768 0 0 1-1.25 0l-.074-.103a1.5 1.5 0 0 1-.091-1.601l.165-.296a.715.715 0 0 1 1.25 0");
}

:global(.vwjnnjbwp) {
  d: path("M3.5 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>

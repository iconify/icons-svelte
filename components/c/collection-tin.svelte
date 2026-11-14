<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3wyxtb6z"/><path class="bro5_6b5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:collection-tin" {...props}></Icon>
<style>
:global(.bro5_6b5x) {
  d: path("M6 11.5v8a6 2.25 0 0 0 12 0v-8m-7.5 0h3M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.f3wyxtb6z) {
  d: path("M6 11.5a6 2.75 0 1 0 12 0a6 2.75 0 1 0-12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nlfj-2b-b"/><path class="qrl6ul59e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hammock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nlfj-2b-b) {
  d: path("M3 4v17M21 4v17M3 8l3 3c3 4.5 9 4.5 12 0l3-3");
}

:global(.qrl6ul59e) {
  d: path("M6 11c3 1.75 9 1.75 12 0");
}

</style>

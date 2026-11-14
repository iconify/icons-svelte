<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrj7-6b7n"/><path class="mv-iezb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:book-index" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mv-iezb2g) {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h11.5m0-12h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2m0 2.5h2a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2");
}

:global(.nrj7-6b7n) {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h11.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

</style>

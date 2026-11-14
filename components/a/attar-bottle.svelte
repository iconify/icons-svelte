<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wcuxuhbah"/><path class="i12f54b4f"/><path class="pa99b8bki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:attar-bottle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i12f54b4f) {
  d: path("M10.25 9.75V7h3.5v2.75");
}

:global(.pa99b8bki) {
  d: path("M9.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

:global(.wcuxuhbah) {
  d: path("M6 15.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

</style>

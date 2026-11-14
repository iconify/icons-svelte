<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q8yna4kqt"/><path class="ejkj6th1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:port-open" {...props}></Icon>
<style>
:global(.ejkj6th1k) {
  d: path("M16.25 15.5h4.25v4.25");
}

:global(.q8yna4kqt) {
  d: path("M13.1 19H2.5V5h19v7.7M6.5 9v6M10 9v6m3.5-6v3.7M15 21l5.25-5.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

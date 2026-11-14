<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f18_f1p2j"/><path class="gf0vx05zh"/><path class="xngn5t3ir"/><path class="oualzjb6b"/><path class="aba_2e7pm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heatmap-taps" {...props}></Icon>
<style>
:global(.aba_2e7pm) {
  d: path("M12.25 14.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM14 10.75v1m3.25 2.75h-1m0-2.25l-.75.75M11 18h2.5");
}

:global(.f18_f1p2j) {
  d: path("M5.5 2.5h13v19h-13Z");
}

:global(.gf0vx05zh) {
  fill: currentColor;
  d: path("M9 8a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.oualzjb6b) {
  fill: currentColor;
  d: path("M13.25 14.5a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xngn5t3ir) {
  d: path("M7.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

</style>

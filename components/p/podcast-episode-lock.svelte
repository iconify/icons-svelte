<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="be63a4byk"/><path class="kojnx9y2b"/><path class="f6t88tu4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:podcast-episode-lock" {...props}></Icon>
<style>
:global(.be63a4byk) {
  d: path("M12.543 21.5H3.5v-19h10l3 3v6.957");
}

:global(.f6t88tu4e) {
  d: path("M7.348 15.652a3.75 3.75 0 1 1 5.304 0M10 14v4.75m6.75-1.25h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kojnx9y2b) {
  d: path("M13.5 2.5v3h3M9 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>

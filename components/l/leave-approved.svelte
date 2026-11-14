<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q1yf41bdr"/><path class="q0jig-8yt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leave-approved" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q0jig-8yt) {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h3.5M9.25 15l2 2l3.5-4");
}

:global(.q1yf41bdr) {
  d: path("M10 2.5h4A3.5 3.5 0 0 1 17.5 6v12a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18V6A3.5 3.5 0 0 1 10 2.5");
}

</style>

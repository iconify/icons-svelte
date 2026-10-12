<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="s43l187bp"/><path class="x8ps3ed8u"/><path class="kddx26bfs"/><path class="u81zjw1kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:file-log-sharp" {...props}></Icon>
<style>
:global(.kddx26bfs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11.25h.01m-.01 3h.01m-.01 3h.01");
}

:global(.s43l187bp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

:global(.u81zjw1kh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 11.25h4m-4 3h4m-4 3h2.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x8ps3ed8u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v5.5h5.5");
}

</style>

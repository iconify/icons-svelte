<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="av_2ehawl"/><path class="d6qw6eo4b"/><path class="co_gj4azy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:database-copy" {...props}></Icon>
<style>
:global(.av_2ehawl) {
  d: path("M3 9a6.5 2.5 0 1 0 13 0A6.5 2.5 0 1 0 3 9");
}

:global(.co_gj4azy) {
  d: path("M10 3.2A6.5 2.5 0 0 1 21 5v10a6.5 2.5 0 0 1-2.25 1.9");
}

:global(.d6qw6eo4b) {
  d: path("M3 9v9.5a6.5 2.5 0 0 0 13 0V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="e3xv68brt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:more-horizontal-circle" {...props}></Icon>
<style>
:global(.e3xv68brt) {
  d: path("M7 12a.75.75 0 1 0 1.5 0A.75.75 0 1 0 7 12Zm4.25 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm4.25 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>

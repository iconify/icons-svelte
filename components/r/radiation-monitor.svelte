<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="zn5p45nvx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:radiation-monitor" {...props}></Icon>
<style>
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

:global(.zn5p45nvx) {
  d: path("M9 12H6a6 6 0 0 1 3-5.25l1.5 2.75A3 3 0 0 0 9 12Zm4.5-2.5L15 6.75A6 6 0 0 1 18 12h-3a3 3 0 0 0-1.5-2.5Zm0 5l1.5 2.75a6 6 0 0 1-6 0l1.5-2.75a3 3 0 0 0 3 0ZM12 12h.01");
}

</style>

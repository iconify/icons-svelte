<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xwtmds85o"/><path class="r-me36u2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:golf-bag" {...props}></Icon>
<style>
:global(.r-me36u2m) {
  d: path("M16.25 10.5q4.75 4-.5 8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwtmds85o) {
  d: path("M7.5 8h9l-1 13.5h-7Zm1.75 0L6.5 3L4 3.75M12 8V2.5l-2 .25M14.75 8l2.75-5l2.5.75");
}

</style>

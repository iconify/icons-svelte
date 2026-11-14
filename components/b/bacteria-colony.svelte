<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="rsvw_ob9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bacteria-colony" {...props}></Icon>
<style>
:global(.rsvw_ob9o) {
  d: path("M9.606 18.578a7 7 0 0 1-3.95-3.62M9 11.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.75-1h.01m-.76 5h.01m-5.01 1h.01");
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

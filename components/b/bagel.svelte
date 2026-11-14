<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ddgawbqpo"/><path class="ocvh0sbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bagel" {...props}></Icon>
<style>
:global(.ddgawbqpo) {
  d: path("M2.5 12a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0Z");
}

:global(.ocvh0sbne) {
  d: path("M8.5 11.5a3.5 1.75 0 1 0 7 0a3.5 1.75 0 1 0-7 0Zm-2.75 0h.01m12.49 0h.01M12 16.25h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

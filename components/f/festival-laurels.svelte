<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2h4pq82x"/><path class="p74vr_d0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:festival-laurels" {...props}></Icon>
<style>
:global(.d2h4pq82x) {
  d: path("M10 20.5c-4.5-1-7-5-6.5-11.5M14 20.5c4.5-1 7-5 6.5-11.5m-17-3.5a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Zm15 0a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Z");
}

:global(.p74vr_d0d) {
  d: path("M5.5 12a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Zm11 0a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0ZM8 17a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Zm6 0a1 2.25 0 1 0 2 0a1 2.25 0 1 0-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

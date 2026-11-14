<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j8f8s_r_s"/><path class="szr4o0iul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:action-figure" {...props}></Icon>
<style>
:global(.j8f8s_r_s) {
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 12.5L8 9h8l3 3.5");
}

:global(.szr4o0iul) {
  d: path("M9.5 9v5l-1 5m6-10v5l1 5m-10 0h13v2.5h-13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8-3qnbwk"/><path class="x6w85zgur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:paper-bag-handles" {...props}></Icon>
<style>
:global(.e8-3qnbwk) {
  d: path("M4.5 9.5h15l-1 12h-13Zm3 0c0-7 9-7 9 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x6w85zgur) {
  d: path("M9.5 9.5c0-4.5 5-4.5 5 0m-9.75 3.25h14.5");
}

</style>

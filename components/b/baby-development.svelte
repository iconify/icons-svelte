<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ssc-57bon"/><path class="avlwy0bzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baby-development" {...props}></Icon>
<style>
:global(.avlwy0bzk) {
  d: path("m5.5 19l1.75-4.25L9 19m5.75-2.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 5.5v3");
}

:global(.ssc-57bon) {
  d: path("M3 12.5h8.5V21H3Zm9.5 0H21V21h-8.5ZM7.75 3h8.5v8.5h-8.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

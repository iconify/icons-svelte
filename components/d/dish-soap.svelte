<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gt78ibbvo"/><path class="hki4d8b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dish-soap" {...props}></Icon>
<style>
:global(.gt78ibbvo) {
  d: path("M6 11a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2Zm3.5-7.5H17v2m-5-2V9");
}

:global(.hki4d8b4z) {
  d: path("M9.5 15.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

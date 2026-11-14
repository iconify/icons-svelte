<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gwuqhybtp"/><path class="ybakmwbam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cat-hammock" {...props}></Icon>
<style>
:global(.gwuqhybtp) {
  d: path("M2.5 20.5L5 3.5h14l2.5 17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybakmwbam) {
  d: path("M7.5 11c2 6 7 6 9 0c-2 2.5-7 2.5-9 0ZM7 3.5l.5 7.5M17 3.5l-.5 7.5");
}

</style>

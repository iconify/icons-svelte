<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="is19_ccqk"/><path class="n84x8cbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grocery-bag-paper" {...props}></Icon>
<style>
:global(.is19_ccqk) {
  d: path("M5 3.5h4.5l2.5 3l2.5-3H19l1 18H4Z");
}

:global(.n84x8cbis) {
  d: path("M7.5 11h9v6h-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ldlj7d90o"/><path class="qh5xhf9pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cash-sorter" {...props}></Icon>
<style>
:global(.ldlj7d90o) {
  d: path("M13.1 17.5H2.5v-13h19v8.1");
}

:global(.qh5xhf9pe) {
  d: path("M7 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11 10.5v-3m0 0l-2.75-2.75M18 18.5v-4m0 4l2.75-2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

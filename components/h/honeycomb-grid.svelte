<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9j8pqose"/><path class="fbyyl5but"/><path class="yqtrv-brv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:honeycomb-grid" {...props}></Icon>
<style>
:global(.fbyyl5but) {
  d: path("m9.5 8l2 1v2.5l-2 1l-2-1V9Z");
}

:global(.i9j8pqose) {
  d: path("M2.5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yqtrv-brv) {
  d: path("m7.5 11.5l2 1V15l-2 1l-2-1v-2.5Zm4 0l2 1V15l-2 1l-2-1v-2.5Zm6.75-4l3.25-2m-3.25 11l3.25 2");
}

</style>

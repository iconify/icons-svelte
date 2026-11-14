<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x761lkbqw"/><path class="vjzs7bcxa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:active-users" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vjzs7bcxa) {
  fill: currentColor;
  d: path("M15 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.x761lkbqw) {
  d: path("M13.072 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.789 0 1.543.078 2.249.225M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>

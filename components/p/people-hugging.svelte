<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r9ab_o_7t"/><path class="bjxeiwbbv"/><path class="rtaomjblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:people-hugging" {...props}></Icon>
<style>
:global(.bjxeiwbbv) {
  d: path("M5.75 15C9 15 12 17 14 19.5");
}

:global(.r9ab_o_7t) {
  d: path("M4.5 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm9 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-11 15v-5c0-2.5 2-4.25 5-4.25h9c3 0 5 1.75 5 4.25v5");
}

:global(.rtaomjblp) {
  d: path("M18.25 15C15 15 12 17 10 19.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

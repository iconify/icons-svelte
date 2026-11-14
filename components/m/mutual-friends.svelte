<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq8rxzn4p"/><path class="iqh7t6b7l"/><path class="r5cjekb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mutual-friends" {...props}></Icon>
<style>
:global(.iqh7t6b7l) {
  d: path("M10.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM3 20.5C3 17.25 5.75 15 9.5 15s6.5 2.25 6.5 5.5");
}

:global(.r5cjekb_s) {
  d: path("M8 20.5c0-3.25 2.75-5.5 6.5-5.5s6.5 2.25 6.5 5.5");
}

:global(.rq8rxzn4p) {
  d: path("M5.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e08sp0b6y"/><path class="mkp-21kph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lamp-post-curved" {...props}></Icon>
<style>
:global(.e08sp0b6y) {
  d: path("M5 21.5h6m-3 0V8c0-3 2-4.5 5-4.5h3.5V5");
}

:global(.mkp-21kph) {
  d: path("M13 8.5Q13 5 16.5 5T20 8.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ceuc7nniz"/><path class="alzandbak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roundabout-exit-back" {...props}></Icon>
<style>
:global(.alzandbak) {
  d: path("M6.75 19.25L9 21.5l2.25-2.25");
}

:global(.ceuc7nniz) {
  d: path("M15 21.5V14a5 5 0 1 0-6 0v7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

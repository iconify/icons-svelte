<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="efjy78b9o"/><path class="ssd2uibvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:astronaut-wave" {...props}></Icon>
<style>
:global(.efjy78b9o) {
  d: path("M4.75 7.75a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0ZM3 21.5c0-3.5 3-5.75 7-5.75s7 2.25 7 5.75m-1.5-4l4.5-12");
}

:global(.ssd2uibvh) {
  d: path("M7.5 6.25h5v3h-5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

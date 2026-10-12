<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="q6j43looo"/><path class="vjgv__-rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fulfillment-center-sharp" {...props}></Icon>
<style>
:global(.q6j43looo) {
  d: path("M2.75 21.25V9.4l.002-.559l.478-.291l4.5-2.7l.787-.505l-.017.935V9l4.73-2.84l.787-.505L14 6.59V9l4.73-2.84l.787-.505l-.017.935v14.66Z");
}

:global(.vjgv__-rw) {
  d: path("M8.5 13.75h7v7.5h-7zm3.5 0v2.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

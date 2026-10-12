<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wt5v8fn7q"/><path class="d8_m3qbgs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bedtime-routine-sharp" {...props}></Icon>
<style>
:global(.d8_m3qbgs) {
  d: path("m5.5 11.5l1 1l1.75-1.75m1.5.75h1.5M5.5 16l1 1l1.75-1.75m1.5.75h1.5m6.57-12.97a3 3 0 1 0 3.4 3.4a2.5 2.5 0 0 1-3.4-3.4Z");
}

:global(.wt5v8fn7q) {
  d: path("M2.75 7h11v14.25h-11z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

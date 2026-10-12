<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="le1-fccpz"/><path class="gdayiybsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:laptop-and-phone-sharp" {...props}></Icon>
<style>
:global(.gdayiybsd) {
  d: path("M15.75 10.25h5.5v11h-5.5zm2 8.25h1.5");
}

:global(.le1-fccpz) {
  d: path("M5.75 3.75h14v3.5h-7v7.5h-9v-11zm-3 14.5h9.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

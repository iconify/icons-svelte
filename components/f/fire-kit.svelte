<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cgydtgkll"/><path class="l9g52x2mc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-kit" {...props}></Icon>
<style>
:global(.cgydtgkll) {
  d: path("M12 12a3.5 3.5 0 0 1-3.5-3.5c0-2 1.25-3.75 2.5-6c1 1.5 2 2.75 2.5 4C14.25 5.75 14.75 5 15 4c.5 1.5.5 3 .5 4.5A3.5 3.5 0 0 1 12 12Zm-7 4.75a7 2 0 1 0 14 0a7 2 0 1 0-14 0Z");
}

:global(.l9g52x2mc) {
  d: path("M5 16.75v2.5a7 2.5 0 0 0 14 0v-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

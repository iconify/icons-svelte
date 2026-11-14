<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="v-jm77swm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:meter-keypad" {...props}></Icon>
<style>
:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v-jm77swm) {
  d: path("M8 10a4 4 0 0 1 8 0m-4 0l2.25-2.25M8.5 14.5h.01m3.49 0h.01m3.49 0h.01M8.5 18h.01M12 18h.01m3.49 0h.01");
}

</style>

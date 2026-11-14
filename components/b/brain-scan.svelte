<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cz4bulbdf"/><path class="nfv18zbbp"/><path class="es7q9r3ig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:brain-scan" {...props}></Icon>
<style>
:global(.cz4bulbdf) {
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m6.25 1.75V16c-1.5-1-2.25-2.5-2.25-4.25C7.5 9 9.5 7 12.25 7c2.5 0 4.25 1.75 4.25 4.25l.75 1.75l-.75.25v1.25c0 .75-.5 1.25-1.25 1.25h-1v2");
}

:global(.es7q9r3ig) {
  d: path("M2.5 12h2.25m14.5 0h2.25");
}

:global(.nfv18zbbp) {
  fill: currentColor;
  d: path("M9.5 10.75a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

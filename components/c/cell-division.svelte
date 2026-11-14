<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgbstdrbw"/><path class="npp3hwbsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cell-division" {...props}></Icon>
<style>
:global(.npp3hwbsn) {
  d: path("M5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zgbstdrbw) {
  d: path("M12 9.25C10.75 7 9 6 7 6c-2.75 0-4.5 2.75-4.5 6s1.75 6 4.5 6c2 0 3.75-1 5-3.25C13.25 17 15 18 17 18c2.75 0 4.5-2.75 4.5-6S19.75 6 17 6c-2 0-3.75 1-5 3.25Z");
}

</style>

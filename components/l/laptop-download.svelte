<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sget-mber"/><path class="nqrh00bso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:laptop-download" {...props}></Icon>
<style>
:global(.nqrh00bso) {
  d: path("M9.75 9.75L12 12l2.25-2.25");
}

:global(.sget-mber) {
  d: path("M4.5 4.5h15v11h-15Zm-2 14h19M12 6.5V12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

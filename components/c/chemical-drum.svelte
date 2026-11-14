<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qc820dtfb"/><path class="dal0q1bok"/><path class="ikfh12bws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chemical-drum" {...props}></Icon>
<style>
:global(.dal0q1bok) {
  d: path("M5 4v16a7 1.5 0 0 0 14 0V4M5 8.25h14m-14 9.5h14");
}

:global(.ikfh12bws) {
  d: path("M12 10.75L14.25 13L12 15.25L9.75 13Z");
}

:global(.qc820dtfb) {
  d: path("M5 4a7 1.5 0 1 0 14 0A7 1.5 0 1 0 5 4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

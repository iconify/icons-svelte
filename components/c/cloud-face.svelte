<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sxxlqnxqs"/><path class="rrrff57nu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cloud-face" {...props}></Icon>
<style>
:global(.rrrff57nu) {
  d: path("M9.5 14.25a3 3 0 0 0 5 0");
}

:global(.sxxlqnxqs) {
  d: path("M7 19h10c2.5 0 4.5-2 4.5-4.5S19.5 10 17 10c-.5-3.5-3-5.5-6-5.5c-3.5 0-6 2.5-6 6c-1.5.5-2.5 2.25-2.5 4.25C2.5 17 4.5 19 7 19Zm2.5-7.5h.01m4.99 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

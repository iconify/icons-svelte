<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s6rxynbgg"/><path class="kqfziyxex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rfid-tag-clothing" {...props}></Icon>
<style>
:global(.kqfziyxex) {
  d: path("M9.702 15.702a3.25 3.25 0 0 1 4.596 0m-6.48-2.347a6.25 6.25 0 0 1 8.364 0");
}

:global(.s6rxynbgg) {
  d: path("m6 7l6-4.5L18 7v14.5H6Zm6 0h.01M12 18h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

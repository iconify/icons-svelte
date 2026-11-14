<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxjpxx18k"/><path class="lq75jrhhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heart-calendar-feb" {...props}></Icon>
<style>
:global(.lq75jrhhc) {
  fill: currentColor;
  d: path("M12 17c-3-2-3.5-3.5-3.5-4.75c0-1.5 2-2.25 3.5-.75c1.5-1.5 3.5-.75 3.5.75C15.5 13.5 15 15 12 17Z");
}

:global(.mxjpxx18k) {
  d: path("M3 4.5h18v17H3Zm5-2v4m8-4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

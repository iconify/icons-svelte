<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o4e904b0z"/><path class="ybi6g3zif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-microscope" {...props}></Icon>
<style>
:global(.o4e904b0z) {
  d: path("M3 20.5h9.5m-2 0V12c0-2.5-1-4-2.75-4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybi6g3zif) {
  d: path("m2.734 3.911l3.032-1.75l4 6.928l-3.032 1.75ZM4 14h6.5M14 6.5h7.5v7H14Zm3.75 3.5h.01m-.01 3.5v7m-2.25 0H20");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoz3zibrm"/><path class="j2beleb3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:e-ink-display" {...props}></Icon>
<style>
:global(.eoz3zibrm) {
  d: path("M4.5 2.5h15v19h-15Z");
}

:global(.j2beleb3z) {
  d: path("M7.25 5.25h9.5v11.5h-9.5ZM10 8h4m-4 3h4m-4 3h2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

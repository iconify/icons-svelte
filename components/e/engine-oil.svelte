<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vj8xqhbbu"/><path class="n4fwfib6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:engine-oil" {...props}></Icon>
<style>
:global(.n4fwfib6c) {
  d: path("M12 11s2.5 2.5 2.5 4.25a2.5 2.5 0 0 1-5 0C9.5 13.5 12 11 12 11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vj8xqhbbu) {
  d: path("m5 10l3.5-3.5H17a2 2 0 0 1 2 2V19a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Zm5-7.5h4v4h-4Z");
}

</style>

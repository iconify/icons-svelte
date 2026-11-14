<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q3mysacze"/><path class="bzqoa2bdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:beach-hut" {...props}></Icon>
<style>
:global(.bzqoa2bdn) {
  d: path("M10 14.5h4v6h-4ZM3.5 21h17");
}

:global(.q3mysacze) {
  d: path("m4 12l8-7.5l8 7.5Zm1.5 0h13v8.5h-13Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

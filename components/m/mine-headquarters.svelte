<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tc-q8acoq"/><path class="ucg8oxbyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mine-headquarters" {...props}></Icon>
<style>
:global(.tc-q8acoq) {
  d: path("M4 7h13v14H4ZM2.5 7h16M4 14.75h13M14.5 7V2m0 0L19 3.75L14.5 5.5ZM2 21h20");
}

:global(.ucg8oxbyw) {
  d: path("M6.75 9.75H9V12H6.75Zm5.25 0h2.25V12H12ZM6.75 17.5H9v2.25H6.75Zm5.25 0h2.25V21H12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

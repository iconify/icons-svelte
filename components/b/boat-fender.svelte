<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="csqvb1b3h"/><path class="ly9wi1bue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boat-fender" {...props}></Icon>
<style>
:global(.csqvb1b3h) {
  d: path("M21.5 4H4c0 8 1 13 4.5 17.5");
}

:global(.ly9wi1bue) {
  d: path("M13 8h4a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-4a1.5 1.5 0 0 1-1.5-1.5V9.5A1.5 1.5 0 0 1 13 8Zm2-4v4m-3.5 6.25h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

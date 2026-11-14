<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="x959kqera"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:button-deck" {...props}></Icon>
<style>
:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x959kqera) {
  d: path("M5.25 6.75h4.5v3.5h-4.5Zm9 0h4.5v3.5h-4.5Zm-9 7h4.5v3.5h-4.5Zm9 0h4.5v3.5h-4.5Z");
}

</style>

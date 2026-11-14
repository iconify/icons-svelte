<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy7z_ac1b"/><path class="e2ok8rb2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:person-arms-crossed" {...props}></Icon>
<style>
:global(.e2ok8rb2g) {
  d: path("M7 15.75h10v3.5H7Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yy7z_ac1b) {
  d: path("M8.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-4 15V17c0-2.75 3.25-4.25 7.5-4.25s7.5 1.5 7.5 4.25v4.5");
}

</style>

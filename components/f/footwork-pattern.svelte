<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eue6xhi8g"/><path class="my0mz_8ml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:footwork-pattern" {...props}></Icon>
<style>
:global(.eue6xhi8g) {
  d: path("M3.5 20L9 14l5 4.5l6-7");
}

:global(.my0mz_8ml) {
  d: path("M16.75 11.75L20 11.5l.25 3.25M3.75 8.5a2.25 3.5 0 1 0 4.5 0a2.25 3.5 0 1 0-4.5 0Zm7.5-1a2.25 3.5 0 1 0 4.5 0a2.25 3.5 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

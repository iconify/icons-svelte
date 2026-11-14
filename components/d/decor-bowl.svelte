<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mblo0noeo"/><path class="lh5e97fgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:decor-bowl" {...props}></Icon>
<style>
:global(.lh5e97fgk) {
  d: path("m9.5 13.25l-1 4.25h7l-1-4.25");
}

:global(.mblo0noeo) {
  d: path("M2.5 7h19a9.5 6.5 0 0 1-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

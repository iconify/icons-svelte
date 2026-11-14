<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nvebvjbad"/><path class="xcgk2tifr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:astronomy-class" {...props}></Icon>
<style>
:global(.nvebvjbad) {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xcgk2tifr) {
  d: path("M2.5 12a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0ZM19 5h.01M5 19h.01");
}

</style>

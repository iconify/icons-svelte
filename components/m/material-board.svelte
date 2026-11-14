<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="ayxlxvb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:material-board" {...props}></Icon>
<style>
:global(.ayxlxvb9x) {
  d: path("M5.5 12V6.5a1 1 0 0 1 1-1H12m-3.25 9.75v-5.5a1 1 0 0 1 1-1h5.5M12 12h6.5v6.5H12Z");
}

:global(.g6ulkabjn) {
  d: path("M2.5 2.5h19v19h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

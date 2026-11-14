<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j12aavbbl"/><path class="n535y5vax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:music-cast-off" {...props}></Icon>
<style>
:global(.j12aavbbl) {
  d: path("M12.6 16.5H2.5v-13h19v13h-1.1m-8.4 0v4m-4 0h8");
}

:global(.n535y5vax) {
  d: path("M8.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0V6.5l2.75 1m1 8l6 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

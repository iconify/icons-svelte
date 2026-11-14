<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c3d6ljbkk"/><path class="rl6808b-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-up" {...props}></Icon>
<style>
:global(.c3d6ljbkk) {
  d: path("M3.5 5h17v15.5h-17ZM8 3v4m8-4v4M3.5 10h17M12 17.75v-5");
}

:global(.rl6808b-h) {
  d: path("M9.75 15L12 12.75L14.25 15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tukh9ubii"/><path class="vp7oxebgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ortho-retainer" {...props}></Icon>
<style>
:global(.tukh9ubii) {
  d: path("M4.5 19v-5.5a7.5 7.5 0 0 1 15 0V19a2 2 0 0 1-4 0v-5.5a3.5 3.5 0 0 0-7 0V19a2 2 0 0 1-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vp7oxebgj) {
  d: path("M3 8.5a10.25 10.25 0 0 1 18 0M12 6v3.75m5.25-1.5L14.5 11M6.75 8.25L9.5 11");
}

</style>

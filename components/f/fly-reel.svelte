<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdrenqb2u"/><path class="mcvcaybeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fly-reel" {...props}></Icon>
<style>
:global(.jdrenqb2u) {
  d: path("M4 12.5a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

:global(.mcvcaybeq) {
  d: path("M9 4.5v-2h6v2m-5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM16 9h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

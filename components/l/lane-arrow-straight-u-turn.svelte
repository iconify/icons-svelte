<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cv49yqkag"/><path class="s8epzqb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-arrow-straight-u-turn" {...props}></Icon>
<style>
:global(.cv49yqkag) {
  d: path("M15.5 21.5V3m-5 5l5-5l5 5m-5 4h-6a4 4 0 0 0-4 4v4.5");
}

:global(.s8epzqb0c) {
  d: path("m3 18l2.5 2.5L8 18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

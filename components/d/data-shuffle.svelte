<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kstoa4xmg"/><path class="gqg6zkbme"/><path class="pstn25chr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-shuffle" {...props}></Icon>
<style>
:global(.gqg6zkbme) {
  d: path("M3.5 17H8c5 0 3-10 8-10h3m-2 8l2.5 2l-2.5 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kstoa4xmg) {
  d: path("M3.5 7H8c5 0 3 10 8 10h3");
}

:global(.pstn25chr) {
  d: path("m17 5l2.5 2L17 9");
}

</style>

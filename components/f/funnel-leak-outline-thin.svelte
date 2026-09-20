<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bdb2pqp3q"/><path class="d05ifsb6w"/><path class="bytnyw6tw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funnel-leak-outline-thin" {...props}></Icon>
<style>
:global(.bdb2pqp3q) {
  d: path("M3 3h18l-7 7v6h-4v-6Z");
}

:global(.bytnyw6tw) {
  d: path("M19.5 16v2.5");
}

:global(.d05ifsb6w) {
  d: path("M17.5 12v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

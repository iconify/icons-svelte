<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yms02xb-d"/><path class="h3lhy7v2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:corrosive" {...props}></Icon>
<style>
:global(.h3lhy7v2b) {
  d: path("M10 7.5c1 1.25 1.5 2 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.75.5-1.5 1.5-2.75M14 9c1 1.25 1.5 2 1.5 2.75a1.5 1.5 0 0 1-3 0c0-.75.5-1.5 1.5-2.75m-6 7h2.75L12 17.25L13.25 16H16");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yms02xb-d) {
  d: path("m13.59 3.84l6.57 6.57q1.59 1.59 0 3.18l-6.57 6.57q-1.59 1.59-3.18 0l-6.57-6.57q-1.59-1.59 0-3.18l6.57-6.57q1.59-1.59 3.18 0");
}

</style>

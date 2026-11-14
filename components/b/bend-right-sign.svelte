<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yh3o8-b_d"/><path class="mc7c4obtw"/><path class="t4d2iabfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bend-right-sign" {...props}></Icon>
<style>
:global(.mc7c4obtw) {
  d: path("M11 16.5v-4a2.5 2.5 0 0 1 2.5-2.5h2");
}

:global(.t4d2iabfw) {
  d: path("m13.75 8l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yh3o8-b_d) {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Z");
}

</style>

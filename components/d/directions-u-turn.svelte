<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yh3o8-b_d"/><path class="swwxl7pak"/><path class="izm8epb2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:directions-u-turn" {...props}></Icon>
<style>
:global(.izm8epb2z) {
  d: path("m12.5 13l2 2l2-2");
}

:global(.swwxl7pak) {
  d: path("M9.5 15.5V11a2.5 2.5 0 0 1 5 0v4");
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

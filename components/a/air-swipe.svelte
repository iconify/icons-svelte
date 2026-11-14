<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hneliqdkn"/><path class="akc5t163v"/><path class="d1qyx9boj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:air-swipe" {...props}></Icon>
<style>
:global(.akc5t163v) {
  d: path("M11 16q2-6 7.5-4.75");
}

:global(.d1qyx9boj) {
  d: path("m17 8.75l1.5 2.5l-2.5 1.5M5.5 16H8m-2-3.5h2.5");
}

:global(.hneliqdkn) {
  d: path("M2.5 4h19v16h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

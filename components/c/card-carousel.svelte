<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="en0djobdx"/><path class="eboc3hbqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:card-carousel" {...props}></Icon>
<style>
:global(.eboc3hbqs) {
  d: path("M6.5 7V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v5.5m-5 3.5l3 3l-3 3");
}

:global(.en0djobdx) {
  d: path("M15.6 18H2.5V7h15v5.1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

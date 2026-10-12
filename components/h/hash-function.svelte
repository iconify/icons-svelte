<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq2-zvyzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hash-function" {...props}></Icon>
<style>
:global(.rq2-zvyzq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5.75L9 18.25m6-12.5l-1.5 12.5m-6.5-9h10m-10.75 5.5h10M2.75 12h2.5m13.5 0h2.5m-1.5-1.75l1.5 1.75l-1.5 1.75");
}

</style>

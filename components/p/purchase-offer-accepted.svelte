<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7oyybqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:purchase-offer-accepted" {...props}></Icon>
<style>
:global(.yt7oyybqh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.5h3.5a4.75 4.75 0 0 1 4.75 4.75A4.75 4.75 0 0 1 13.75 12h-3.5A4.75 4.75 0 0 1 5.5 7.25a4.75 4.75 0 0 1 4.75-4.75M12 12v5.9m0 .2v3.4M12 5v4.5m2.75 8.5l2 2L21 15.75");
}

</style>

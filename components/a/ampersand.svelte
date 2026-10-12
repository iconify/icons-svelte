<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkuoqpbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ampersand" {...props}></Icon>
<style>
:global(.rkuoqpbcm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.5 20.25l-10.75-11C7.5 8 7 7 7 6c0-1.5 1.25-2.75 2.75-2.75S12.5 4.5 12.5 6c0 1.75-1.5 2.75-4 4.25c-2.25 1.25-3.75 2.75-3.75 5c0 2.5 2 4.75 4.75 4.75c3 0 5.75-2 7.5-5.75");
}

</style>

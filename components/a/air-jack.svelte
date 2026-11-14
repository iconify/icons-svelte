<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygerdsd4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:air-jack" {...props}></Icon>
<style>
:global(.ygerdsd4n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4h8m-4 0l7 8l-7 8l-7-8ZM5 20h14M2.5 12h19");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bitd0ccgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camisole" {...props}></Icon>
<style>
:global(.bitd0ccgk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9q4.5 5.5 9 0l2 4.5V21h-13v-7.5Zm0 0L8 3m8.5 6L16 3");
}

</style>

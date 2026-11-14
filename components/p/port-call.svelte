<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw5_g0-4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:port-call" {...props}></Icon>
<style>
:global(.cw5_g0-4n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5H16L14.5 14H4Zm2.5 0V4h6v4.5M17.5 20v-5.5h4m-5.5-6l4 6");
}

</style>

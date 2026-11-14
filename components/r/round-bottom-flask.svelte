<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz4_y5bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:round-bottom-flask" {...props}></Icon>
<style>
:global(.fz4_y5bcc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v6.25a6.5 6.5 0 1 0 4 0V3M8.5 3h7M6.25 15.5h11.5");
}

</style>

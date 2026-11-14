<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-rtpjfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dotted-note" {...props}></Icon>
<style>
:global(.ex-rtpjfk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 18a3.5 2.5 0 1 0 7 0a3.5 2.5 0 1 0-7 0m7 0V3.5M18 18h.01");
}

</style>

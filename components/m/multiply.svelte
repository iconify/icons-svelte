<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3u37fwpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:multiply" {...props}></Icon>
<style>
:global(.a3u37fwpg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 7l10 10m0-10L7 17");
}

</style>

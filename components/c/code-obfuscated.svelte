<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bos09op3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-obfuscated" {...props}></Icon>
<style>
:global(.bos09op3c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 7l-5 5l5 5m9-10l5 5l-5 5M12 8.5v7m-3-5.25l6 3.5m0-3.5l-6 3.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc0_t9bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-slash" {...props}></Icon>
<style>
:global(.gc0_t9bxg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 4.5l-4 15M14 7l5 5l-5 5");
}

</style>

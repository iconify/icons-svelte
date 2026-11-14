<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrlw2cc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:digital-signal" {...props}></Icon>
<style>
:global(.qrlw2cc2d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17H6V7h4.5v10h4V7H18v10h3.5");
}

</style>

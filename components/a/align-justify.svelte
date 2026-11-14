<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8ce81bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:align-justify" {...props}></Icon>
<style>
:global(.n8ce81bnq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h17M3.5 10h17m-17 4.5h17M3.5 19h17");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_gbsrbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:circuit-symbol-battery" {...props}></Icon>
<style>
:global(.q_gbsrbbe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h7m5 0h7m-12-6v12m5-9.5v7");
}

</style>

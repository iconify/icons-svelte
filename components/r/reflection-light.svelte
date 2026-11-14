<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygx3n07xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reflection-light" {...props}></Icon>
<style>
:global(.ygx3n07xv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17h15m-17-9.5L12 17l9.5-9.5m-3.5 0h3.5V11");
}

</style>

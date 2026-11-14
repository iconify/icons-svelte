<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lskdn53pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pipe-command" {...props}></Icon>
<style>
:global(.lskdn53pi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5v17m18-17v17M7 12h10m-3.5-3.5L17 12l-3.5 3.5");
}

</style>

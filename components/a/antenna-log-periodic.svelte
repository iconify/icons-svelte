<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j79b5nbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:antenna-log-periodic" {...props}></Icon>
<style>
:global(.j79b5nbhz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-2.5-17h5m-7 4h9m-11 4h13m-15 4h17");
}

</style>

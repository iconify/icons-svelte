<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fft6-terv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:inbox-down" {...props}></Icon>
<style>
:global(.fft6-terv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h5l1.5 2.5h5L16 12h5v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm9-9v7M9 7l3 3l3-3");
}

</style>

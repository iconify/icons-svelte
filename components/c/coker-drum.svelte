<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jja_jwb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coker-drum" {...props}></Icon>
<style>
:global(.jja_jwb0e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5a5 3.5 0 0 1 10 0V16a5 3.5 0 0 1-10 0Zm1.5 12v3m7-3v3");
}

</style>

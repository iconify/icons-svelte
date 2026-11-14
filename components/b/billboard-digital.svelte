<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1o4yacyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:billboard-digital" {...props}></Icon>
<style>
:global(.v1o4yacyc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12a3.5 3.5 0 0 1 3.5 3.5V12a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12V6.5A3.5 3.5 0 0 1 6 3m1 12.5V21m10-5.5V21M12 3v12.5M2.5 9.25h19");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch2apac6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bitts" {...props}></Icon>
<style>
:global(.ch2apac6e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 19V7.5h-1V5h6v2.5h-1V19m5 0V7.5h-1V5h6v2.5h-1V19m-16 0h19m-12-7h5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxsh7_c0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:reaction-arrow" {...props}></Icon>
<style>
:global(.nxsh7_c0g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19m-6-6l6 6l-6 6");
}

</style>

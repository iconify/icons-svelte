<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3lejundu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frame" {...props}></Icon>
<style>
:global(.i3lejundu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5v19m10-19v19M2.5 7h19m-19 10h19");
}

</style>

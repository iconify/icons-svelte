<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg-jnsf3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quote-block" {...props}></Icon>
<style>
:global(.fg-jnsf3v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4v16m5-11h12m-12 6H16");
}

</style>

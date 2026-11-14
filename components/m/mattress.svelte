<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp6rslj4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mattress" {...props}></Icon>
<style>
:global(.dp6rslj4g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17V7h16a3 3 0 0 1 3 3v7Zm0-7h19m-19 4h19");
}

</style>

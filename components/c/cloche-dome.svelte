<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vskzneorb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cloche-dome" {...props}></Icon>
<style>
:global(.vskzneorb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16c0-5.5 4-9 8.5-9s8.5 3.5 8.5 9Zm-1 3h19M12 7V4.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw1mus7ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dish-lnb" {...props}></Icon>
<style>
:global(.jw1mus7ev) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.5a9 9 0 0 0 12 12Zm6 6l5.25-5.25M15.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M6.5 17.75v3.75m-3 0h6");
}

</style>

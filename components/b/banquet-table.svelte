<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myhky_bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:banquet-table" {...props}></Icon>
<style>
:global(.myhky_bnr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 12a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0M9.5 3h5m-5 18h5M3 9.5v5m18-5v5");
}

</style>

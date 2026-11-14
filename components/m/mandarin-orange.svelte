<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k19a4nfaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mandarin-orange" {...props}></Icon>
<style>
:global(.k19a4nfaq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.75a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0M12 6V2.5m0 1C10.5 2 8 2 6 3c2 1.25 4.5 1.5 6 .5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji49wacnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hashtag-trend-sharp" {...props}></Icon>
<style>
:global(.ji49wacnu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 8.5l-1.5 12.25m6.5-12.25l-1.5 12.25M4 12.25h10.5M3.25 17h10.5m.75-7.5L17.75 6l1.75 1.75L21.25 6m-3.5-2.25h3v3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwe6nsblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:charger-plug-in" {...props}></Icon>
<style>
:global(.fwe6nsblb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7h12v4a6 6 0 0 1-6 6a6 6 0 0 1-6-6Zm3-4.5V7m6-4.5V7m-3 10v4.5");
}

</style>

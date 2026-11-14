<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it5agcdwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lightning-strike" {...props}></Icon>
<style>
:global(.it5agcdwc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.5 3l-8 10h5.25L10 18.5l7.5-9h-5Zm-11 18.25h17M5.5 17L7 18.5m7.5 0L16 17");
}

</style>

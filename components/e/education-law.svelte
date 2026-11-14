<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eptwmnbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:education-law" {...props}></Icon>
<style>
:global(.eptwmnbzd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5c-3-2-6.5-2.5-9.5-2v-7c3-.5 6.5 0 9.5 2c3-2 6.5-2.5 9.5-2v7c-3-.5-6.5 0-9.5 2Zm0-7v7m0-18l8 3l-8 3l-8-3Zm5.5 4V10");
}

</style>

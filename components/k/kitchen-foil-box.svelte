<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmxvhubnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kitchen-foil-box" {...props}></Icon>
<style>
:global(.zmxvhubnu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h19v7h-19Zm0 3h19M6 12v5.5L8 19l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5V12");
}

</style>

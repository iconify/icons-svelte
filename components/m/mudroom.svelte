<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yosv5obmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mudroom" {...props}></Icon>
<style>
:global(.yosv5obmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h4.5v12.5l2.75 1.75v4.25H3Zm10 0h4.5v12.5l2.75 1.75v4.25H13ZM3 6.5h4.5m5.5 0h4.5");
}

</style>

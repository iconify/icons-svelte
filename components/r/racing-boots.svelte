<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbrrbral"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:racing-boots" {...props}></Icon>
<style>
:global(.ggbrrbral) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h6.5V11l5.5 2a2.5 2.5 0 0 1 2.5 2.5v5H5Zm0 15h14.5M5 8h6.5");
}

</style>

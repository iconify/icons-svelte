<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc5bdwb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lead-nurture" {...props}></Icon>
<style>
:global(.gc5bdwb5d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V11M7 21h10m-5-8c0-3.5-2.5-6-7-6c0 3.5 2.5 6 7 6Zm0-2c0-4.5 3-7 8-7c0 4.5-3 7-8 7Z");
}

</style>

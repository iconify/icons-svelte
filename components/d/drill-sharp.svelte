<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy4gv_xfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drill-sharp" {...props}></Icon>
<style>
:global(.yy4gv_xfe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h12v6H3Zm4 6v6m4-6v6m-6 0h8v4H5ZM15 5h3v4h-3m3-2h3");
}

</style>

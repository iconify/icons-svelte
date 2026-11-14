<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlnnd2b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:post-archive" {...props}></Icon>
<style>
:global(.rlnnd2b5m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5V19A2.5 2.5 0 0 0 6 21.5h12a2.5 2.5 0 0 0 2.5-2.5v-6.5M10 17h4M12 2.5V10M9 7l3 3l3-3");
}

</style>

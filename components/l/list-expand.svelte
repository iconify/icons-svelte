<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2txfeexs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:list-expand" {...props}></Icon>
<style>
:global(.l2txfeexs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6h8.5M12 12h8.5M12 18h8.5M3.5 6.5L6 4l2.5 2.5m-5 11L6 20l2.5-2.5");
}

</style>

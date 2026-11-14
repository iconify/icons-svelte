<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuq6_hbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:champagne-glass" {...props}></Icon>
<style>
:global(.vuq6_hbyt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7l-1 10.5c-.25 1.5-1.25 2-2.5 2s-2.25-.5-2.5-2ZM12 15v6.5m-3.5 0h7M12 6.5h.01m-.01 4h.01");
}

</style>

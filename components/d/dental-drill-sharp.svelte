<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwg5y-nez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dental-drill-sharp" {...props}></Icon>
<style>
:global(.vwg5y-nez) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.08 18.19l4.42-6.82l.54-.84l.84-.54l4.78-3.05l.84-.54V4.25H20v6.25h-4l-.91.41l-2.58 1.18l-.91.41l-.52.85l-4.1 6.77l-.52.85l-.83-.55l-1.26-.84l-.83-.55zM17.5 10.5v3.75m2.75-1.5L21 14.5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve09ffb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:customer-service-desk" {...props}></Icon>
<style>
:global(.ve09ffb2d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19v3h-19Zm2 3v6h15v-6M8 9.5a4 4 0 0 1 8 0m-9.5 0h11M12 3v2.5");
}

</style>

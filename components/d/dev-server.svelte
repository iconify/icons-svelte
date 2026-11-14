<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3_epdbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dev-server" {...props}></Icon>
<style>
:global(.m3_epdbgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 14.5H2.5v-12H18v7.7m-8.75 4.3v5m-2.75 0h5.75M15 13h7v9h-7Zm0 4.5h7");
}

</style>

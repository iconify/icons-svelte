<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhiil7c-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cheque-register" {...props}></Icon>
<style>
:global(.jhiil7c-x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h15v19h-15ZM3 6h4.5M3 10h4.5M3 14h4.5M3 18h4.5m3-10.5h.01m2.49 0h4.5m-7 4.5h.01M13 12h4.5m-7 4.5h.01m2.49 0h4.5");
}

</style>

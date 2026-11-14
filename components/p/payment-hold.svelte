<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smbbl_-uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:payment-hold" {...props}></Icon>
<style>
:global(.smbbl_-uv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.7 19H2.5V5h19v7.7m-19-3.2h19m-19 0h19M6 15h2.5m8 .5v5m3-5v5");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6810h1td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:caravanserai" {...props}></Icon>
<style>
:global(.a6810h1td) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21H2.5V10h19v11H15v-4.5a3 3 0 0 0-6 0ZM7 10a5 5 0 0 1 10 0m-5-5V2.75");
}

</style>

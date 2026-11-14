<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otfc6zbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roof-clerestory-monitor" {...props}></Icon>
<style>
:global(.otfc6zbbc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5L8 9h8l5.5 3.5M8 4.5h8V9H8Zm-3.5 9.25V20h15v-6.25M12 4.5V9");
}

</style>

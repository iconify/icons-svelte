<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6unthcvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nfc" {...props}></Icon>
<style>
:global(.r6unthcvi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h10v18H3Zm3.5 14.5h3m5.975-7.975a3.5 3.5 0 0 1 0 4.95M18.362 7.5a7 7 0 0 1 0 9");
}

</style>

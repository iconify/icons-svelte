<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-8_f8bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colour-contrast-check" {...props}></Icon>
<style>
:global(.u-8_f8bne) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h8v8h-8Zm11 0h8v8h-8Zm-11 13H10m-7.5 4H7m7.75-2.5l2 2L21 15.75");
}

</style>

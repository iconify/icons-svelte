<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5xw6ccmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:evidence-box" {...props}></Icon>
<style>
:global(.l5xw6ccmw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h15v4h-15Zm10.2 14H3.5v-10h13v3.6m-1 4.9l2.75-2.75L21 16v5.5h-5.5Z");
}

</style>

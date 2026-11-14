<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5a0a_dtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:baby-girl" {...props}></Icon>
<style>
:global(.q5a0a_dtb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm1-12l12 4v-4l-12 4Zm6 2h.01M9.5 15h.01m4.99 0h.01");
}

</style>

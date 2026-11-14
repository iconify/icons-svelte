<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxb2_kk9n"/><path class="awan9sb2a"/><path class="rhh4v4bgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bale-stack" {...props}></Icon>
<style>
:global(.awan9sb2a) {
  d: path("M7.25 7.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm0 6.5a2 2 0 1 1-2 2m11.5-2a2 2 0 1 1-2 2");
}

:global(.kxb2_kk9n) {
  d: path("M2.5 16.25a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Zm9.5 0a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

:global(.rhh4v4bgw) {
  d: path("M12 5.75a2 2 0 1 1-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

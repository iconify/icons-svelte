<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nur2wpb3a"/><path class="co3lfibsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:forensic-camera" {...props}></Icon>
<style>
:global(.co3lfibsu) {
  d: path("M8 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7.25 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

:global(.nur2wpb3a) {
  d: path("M12.5 18h-10V6h17v6.9M5.5 6V3h4v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

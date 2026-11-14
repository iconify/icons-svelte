<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rspbnh89v"/><path class="o71is4adu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:package-audit" {...props}></Icon>
<style>
:global(.o71is4adu) {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v5.3m0 2.4v2.3m2.75-3.5l2 2L21 15.75");
}

:global(.rspbnh89v) {
  d: path("M13.534 20.688L12 21.5L3.5 17V7L12 2.5L20.5 7v5.282");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ev1xts_jp"/><path class="sukzc79xj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:accountants-office" {...props}></Icon>
<style>
:global(.ev1xts_jp) {
  d: path("M11.46 20H3.5V10l8-7l8 7v.74");
}

:global(.sukzc79xj) {
  d: path("M14.25 13.5H22V22h-7.75Zm2.5 2.75h2.75m-2.75 3h.01m2.74 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

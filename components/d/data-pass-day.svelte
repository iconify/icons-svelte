<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x5wpfgb-s"/><path class="tommqtb3y"/><path class="z87sto2xh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-pass-day" {...props}></Icon>
<style>
:global(.tommqtb3y) {
  fill: currentColor;
  d: path("M6 9.5h3v3H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x5wpfgb-s) {
  d: path("M12.9 16.5H3v-13h13v10.7M7 2v3m5-3v3");
}

:global(.z87sto2xh) {
  d: path("M15.75 19v2m2.75-4v4m2.75-6v6");
}

</style>

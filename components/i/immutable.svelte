<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_aulhxmx"/><path class="oo2hw-bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:immutable" {...props}></Icon>
<style>
:global(.oo2hw-bxb) {
  d: path("M2.5 6.75L11 11l8.5-4.25M11 11v8.5m4-2.5h6v4.5h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_aulhxmx) {
  d: path("M12.169 18.916L11 19.5l-8.5-4.25v-8.5L11 2.5l8.5 4.25v4.897");
}

</style>

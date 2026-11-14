<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_psw1y4g"/><path class="i6natd9uh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-alarm-sign" {...props}></Icon>
<style>
:global(.i6natd9uh) {
  d: path("M12 6.5c2.5 2.5 4 4.5 4 7.25a4 4 0 0 1-8 0c0-1.75.75-3 1.75-4c0 1.25.5 2 1.25 2.25c-.25-2 .25-4 1-5.5Z");
}

:global(.j_psw1y4g) {
  d: path("M3 3h18v18H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

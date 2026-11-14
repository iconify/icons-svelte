<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b6l-yjbas"/><path class="u402xnbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:api-versioning" {...props}></Icon>
<style>
:global(.b6l-yjbas) {
  d: path("M3 2.5h18V11H3Zm0 11.25h18v7.75H3Z");
}

:global(.u402xnbet) {
  d: path("m6.5 5.25l1.75 3l1.75-3m3 1.5h4.5m-11 11H11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pnxh9dbvs"/><path class="j6f1c3fkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lightning-arrestor" {...props}></Icon>
<style>
:global(.j6f1c3fkv) {
  d: path("M13 8.5L11 12h2l-2 3.5");
}

:global(.pnxh9dbvs) {
  d: path("M8 6.5h8v11H8Zm4-4v4m0 11v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

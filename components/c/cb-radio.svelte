<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qnljgeszn"/><path class="o_tvdkr8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cb-radio" {...props}></Icon>
<style>
:global(.o_tvdkr8v) {
  d: path("M5.5 15a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm9-1.75h4m-4 3.5h4");
}

:global(.qnljgeszn) {
  d: path("M2.5 9h19v12h-19Zm15 0L20 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

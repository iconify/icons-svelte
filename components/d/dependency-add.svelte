<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcyc4b3ql"/><path class="hpk3e2vba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dependency-add" {...props}></Icon>
<style>
:global(.hpk3e2vba) {
  d: path("m5.25 13.5l2 2l2-2M18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vcyc4b3ql) {
  d: path("M2.5 3H12v5.5H2.5Zm0 12.5H12V21H2.5Zm4.75-7v7");
}

</style>

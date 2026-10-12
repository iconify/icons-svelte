<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ti6133bws"/><path class="zxnlgy5hq"/><path class="po5lp0myl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:label-maker-sharp" {...props}></Icon>
<style>
:global(.po5lp0myl) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 16h.01M12 16h.01M15 16h.01M9 18.5h.01m2.99 0h.01m2.99 0h.01");
}

:global(.ti6133bws) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.75v-4h6v4m-9.75 0h13.5v14.5H5.25z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zxnlgy5hq) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 9.75h7.5v3h-7.5Z");
}

</style>

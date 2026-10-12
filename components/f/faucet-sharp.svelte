<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="txvwqo0oj"/><path class="t92aii9xn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:faucet-sharp" {...props}></Icon>
<style>
:global(.t92aii9xn) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 19.5h.01");
}

:global(.txvwqo0oj) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h15V15h-4v-2.5h-11Zm5.25 0v-3.5m-2.5 0h5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

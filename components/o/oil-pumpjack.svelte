<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d52r84jgn"/><circle class="qcb5jf56v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:oil-pumpjack" {...props}></Icon>
<style>
:global(.d52r84jgn) {
  d: path("M7.5 5H4.25a1.5 1.5 0 0 0-1.5 1.5v4a3 3 0 0 0 3 3H7.5Zm0 3l13 2.5m-10 10.75L13 9l2.5 12.25m3.75-11V14m-14.5-.5v7.75m-2 0h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qcb5jf56v) {
  cx: 19.25px;
  cy: 16px;
  r: 2px;
}

</style>

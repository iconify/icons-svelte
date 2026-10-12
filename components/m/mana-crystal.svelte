<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nv_j34bdv"/><path class="shazk6b1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mana-crystal" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nv_j34bdv) {
  d: path("m11.21 4.21l3.08 3.08Q15 8 15 9v6.5q0 1-.71 1.71l-3.08 3.08q-.71.71-1.42 0l-3.08-3.08Q6 16.5 6 15.5V9q0-1 .71-1.71l3.08-3.08q.71-.71 1.42 0");
}

:global(.shazk6b1v) {
  d: path("M6.25 8.25L10.5 11l4.25-2.75M10.5 11v9.25M18.25 3q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75q2.42-.33 2.75-2.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i83a83nao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cheque-register" {...props}></Icon>
<style>
:global(.i83a83nao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5h8A3.5 3.5 0 0 1 20.5 6v12a3.5 3.5 0 0 1-3.5 3.5H9A3.5 3.5 0 0 1 5.5 18V6A3.5 3.5 0 0 1 9 2.5M3 6h4.5M3 10h4.5M3 14h4.5M3 18h4.5m3-10.5h.01m2.49 0h4.5m-7 4.5h.01M13 12h4.5m-7 4.5h.01m2.49 0h4.5");
}

</style>

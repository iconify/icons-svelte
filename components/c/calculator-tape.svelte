<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfipu451g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:calculator-tape" {...props}></Icon>
<style>
:global(.cfipu451g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h10a3 3 0 0 1 3 3a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3a3 3 0 0 1 3-3m0 6v11l1.75 1.5L10.5 20l1.75 1.5L14 20l1.75 1.5L17 20.25V9m-7.25 4h4.5m-4.5 3.5h2.75");
}

</style>

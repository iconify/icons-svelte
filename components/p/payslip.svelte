<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpfyvkbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:payslip" {...props}></Icon>
<style>
:global(.kpfyvkbka) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h13v18l-3-2l-3.5 2l-3.5-2l-3 2Zm3 4.5h7m-7 3.5h7m-7 3.5h4");
}

</style>

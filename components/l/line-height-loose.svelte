<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgx1z1upa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:line-height-loose" {...props}></Icon>
<style>
:global(.fgx1z1upa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h17m-17 17h17M12 8v8m-2.5-5.5L12 8l2.5 2.5m-5 3L12 16l2.5-2.5");
}

</style>

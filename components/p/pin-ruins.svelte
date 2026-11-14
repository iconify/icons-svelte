<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf87ncbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-ruins" {...props}></Icon>
<style>
:global(.jf87ncbwo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5m-3-14V15m3-4v4m3-6v6M8 7.5h4.5M8 15h8");
}

</style>

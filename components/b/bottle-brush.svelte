<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytke4j8rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bottle-brush" {...props}></Icon>
<style>
:global(.ytke4j8rw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m3-1.25L20.5 3.5M9.75 9.75l4.5 4.5m-2.5-6.5l4.5 4.5m-2.5-6.5l4.5 4.5m-2.5-6.5l4.5 4.5");
}

</style>

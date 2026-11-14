<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8pe9swvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carrot-plant" {...props}></Icon>
<style>
:global(.r8pe9swvc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19M8 10l3.25 9.75a.75.75 0 0 0 1.5 0L16 10m-4 0V3m0 7c-2-3-3.5-4.5-5.5-5.5M12 10c2-3 3.5-4.5 5.5-5.5");
}

</style>

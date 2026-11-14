<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m89lbv2oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:euro-sign" {...props}></Icon>
<style>
:global(.m89lbv2oa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.321 17.745a7.5 7.5 0 1 1 0-11.49M4 10h9.5M4 14h9.5");
}

</style>

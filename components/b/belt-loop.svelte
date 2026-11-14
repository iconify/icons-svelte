<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1u80ibxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:belt-loop" {...props}></Icon>
<style>
:global(.a1u80ibxq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h19m-19 5h19M9 10v7q0 2 2 2h2q2 0 2-2v-7");
}

</style>

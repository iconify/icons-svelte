<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foe589cqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coverage-report" {...props}></Icon>
<style>
:global(.foe589cqz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3v16.5h9.4m-6.65-3v-6m3.25 6v-11m3.25 11V13m2.5 5l2 2L21 15.75");
}

</style>

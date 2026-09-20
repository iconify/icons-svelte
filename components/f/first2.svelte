<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lqf5v0bhr"/><path class="flovl0bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:first2" {...props}></Icon>
<style>
:global(.flovl0bup) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.979 31.758l4.482-7.763h25.292m-11.646 0V13.69");
}

:global(.lqf5v0bhr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24L13.25 5.38h21.5L45.5 24L34.75 42.62h-21.5zm14.119-10.31h22.929M16.624 34.31h22.924");
}

</style>

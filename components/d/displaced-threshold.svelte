<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qddlxh47i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:displaced-threshold" {...props}></Icon>
<style>
:global(.qddlxh47i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5v19m12-19v19M9 2.75v5m3-5v5m3-5v5M6 10.5h12M12 21v-7.75m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>

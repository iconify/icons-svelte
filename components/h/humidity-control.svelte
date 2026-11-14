<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riqvcctjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:humidity-control" {...props}></Icon>
<style>
:global(.riqvcctjq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5s-6.5 6.5-6.5 11a6.5 6.5 0 0 0 13 0c0-4.5-6.5-11-6.5-11M9.5 15h5");
}

</style>

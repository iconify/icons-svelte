<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6oaxbcgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cut-time" {...props}></Icon>
<style>
:global(.s6oaxbcgs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 6.75a7.5 7.5 0 1 0 0 10.5M12 2.5v19");
}

</style>

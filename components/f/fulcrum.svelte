<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb37rxztm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fulcrum" {...props}></Icon>
<style>
:global(.qb37rxztm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5h19m-9.5 0l5.5 11h-11Z");
}

</style>

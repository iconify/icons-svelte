<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj5gbubvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrows-up-down-alt" {...props}></Icon>
<style>
:global(.vj5gbubvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 20.5v-17m9 0v17m-12-14l3-3l3 3m3 11l3 3l3-3");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpwr9eb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:number-type" {...props}></Icon>
<style>
:global(.tpwr9eb7a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.75 3l-2 18m8.5-18l-2 18M3.5 8.5h17m-17 7h17");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv42ec_4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:approximately-equal" {...props}></Icon>
<style>
:global(.gv42ec_4b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9.5c2.5-2.25 4.5-2.25 7 0s4.5 2.25 7 0m-14 5c2.5-2.25 4.5-2.25 7 0s4.5 2.25 7 0");
}

</style>

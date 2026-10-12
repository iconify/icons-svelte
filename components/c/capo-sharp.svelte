<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsc-7l6lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:capo-sharp" {...props}></Icon>
<style>
:global(.jsc-7l6lf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75v6.5m0 5.5v6.5m7-18.5v6.5m0 5.5v6.5M8.5 5.5h7m-7 13h7M4.25 9.25h15.5v5.5H4.25z");
}

</style>

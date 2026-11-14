<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmyv8ub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:catheter" {...props}></Icon>
<style>
:global(.pmyv8ub6a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h17v11h-17ZM17 7V4.5c0-1.25 1-2 2.25-2h2.25M9.75 18h2.5v2.75h-2.5ZM5 10h2.5M5 12.5h1.5M5 15h2.5");
}

</style>

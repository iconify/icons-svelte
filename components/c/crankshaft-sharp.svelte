<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e9drbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crankshaft-sharp" {...props}></Icon>
<style>
:global(.m8e9drbnm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12h2.5V6.75H11v10.5h3V6.75h3.5V12h3.75M2.75 8.75H5v6.5H2.75z");
}

</style>

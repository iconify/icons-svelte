<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as86lzbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-bar-stacked" {...props}></Icon>
<style>
:global(.as86lzbqr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10H7v11.5H2.5Zm7.25-7.5h4.5v19h-4.5ZM17 13h4.5v8.5H17ZM2.5 15.5H7M9.75 11h4.5M17 17.5h4.5");
}

</style>

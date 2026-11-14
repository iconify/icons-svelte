<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6q-pkyeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:font" {...props}></Icon>
<style>
:global(.z6q-pkyeu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20l5-15.5l5 15.5m-8.25-5h6.5m3.75 1.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6-3.25V20");
}

</style>

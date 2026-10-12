<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsek93b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:griddle-sharp" {...props}></Icon>
<style>
:global(.jsek93b9u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11.5h5v3h-5zm8 0h5v3h-5zm-9 3h15v4h-15zm0 2H2.75m16.75 0h1.75");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo0xobx6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:artboard-plus-sharp" {...props}></Icon>
<style>
:global(.oo0xobx6i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h14v11h-14zm0-3.75h6m8-.75v1.5m3 3h1.5m-1.5 11h1.5m-4.5 3v-1.5");
}

</style>

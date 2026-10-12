<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykp-3ebtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:podcast-mic-sharp" {...props}></Icon>
<style>
:global(.ykp-3ebtx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h9V13.5h-9zm0 5h9m-9 2.75h9m-4.5 3V16m4.5-7.5h3.5v12.75m-4.5 0h8.5");
}

</style>

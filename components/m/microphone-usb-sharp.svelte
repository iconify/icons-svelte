<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pez0vobwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:microphone-usb-sharp" {...props}></Icon>
<style>
:global(.pez0vobwb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75h7.5V15h-7.5zm0 4.25h3.25m-3.25 3h3.25m.5 5v3.5l-4.5 2.75M12 18.5l4.5 2.75");
}

</style>

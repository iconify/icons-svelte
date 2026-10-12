<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be2j7zbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fence-wooden-sharp" {...props}></Icon>
<style>
:global(.be2j7zbfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h3.5v17.75H5zm10.5 0H19v17.75h-3.5zm-8.75 3v.01m10.5-.01v.01M2.75 10h18.5m-18.5 5.75h18.5");
}

</style>

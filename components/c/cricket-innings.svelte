<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7yzo4shx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cricket-innings" {...props}></Icon>
<style>
:global(.d7yzo4shx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.5h5v13h-5Zm2.5 13v6m7-14.5v14.5M16.75 7v14.5M20.25 7v14.5m-7-14.5h7");
}

</style>

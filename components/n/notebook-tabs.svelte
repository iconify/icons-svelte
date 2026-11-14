<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgdk5us9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:notebook-tabs" {...props}></Icon>
<style>
:global(.sgdk5us9g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h14v18H4Zm14 2.5h1.5a1 1 0 0 1 1 1V8a1 1 0 0 1-1 1H18m0 3h1.5a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1H18M8 3v18m3-13h4");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu-0qybet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:column-classical" {...props}></Icon>
<style>
:global(.iu-0qybet) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3h16v3.5H4Zm5 3.5V16m6-9.5V16m-8.5 0h11v2.5h-11ZM3 21.5h18m-9-12V13");
}

</style>

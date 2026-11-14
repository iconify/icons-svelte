<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq8oj4bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:midi-skirt" {...props}></Icon>
<style>
:global(.aq8oj4bac) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9v3h-9Zm1 3l-4 10q7.5 1.5 15 0l-4-10m-6 10.75v5.25m5-5.25v5.25");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2yo59bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:feather-duster" {...props}></Icon>
<style>
:global(.e2yo59bla) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V2.5m0 9.5c-1.5-5-3-8-4.75-9M12 12c1.5-5 3-8 4.75-9M12 12C8 6 4.5 5 3 8m9 4c4-6 7.5-7 9-4m-10.5 4h3v2.75h-3Zm1.5 2.75v6.75");
}

</style>

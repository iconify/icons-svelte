<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yis-tr1ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gaming-table-round" {...props}></Icon>
<style>
:global(.yis-tr1ow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0Zm8 2.5v11m-3 0h4.3m4.764-7.084l5.313 1.424l-1.941 7.244l-5.313-1.424Z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o203fszhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:css-grid" {...props}></Icon>
<style>
:global(.o203fszhj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h8v8h-8Zm11 0h8v8h-8Zm-11 11h8v8h-8Zm13.5 0h-.25a1.25 1.25 0 0 0-1.25 1.25v1.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1 1.25 1.25v1.5a1.25 1.25 0 0 0 1.25 1.25H16m3-8h.25a1.25 1.25 0 0 1 1.25 1.25v1.5a1.25 1.25 0 0 0 1.25 1.25a1.25 1.25 0 0 0-1.25 1.25v1.5a1.25 1.25 0 0 1-1.25 1.25H19");
}

</style>

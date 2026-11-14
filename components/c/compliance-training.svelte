<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixpzelbmk"/><path class="wb7rpab6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compliance-training" {...props}></Icon>
<style>
:global(.ixpzelbmk) {
  d: path("M12 6.5C10 5 6.5 4.5 2.5 5v14c4-.5 7.5 0 9.5 1.5c2-1.5 5.5-2 9.5-1.5V5c-4-.5-7.5 0-9.5 1.5Zm0 0v14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wb7rpab6r) {
  d: path("m14.75 12l1.5 1.5L19 10");
}

</style>

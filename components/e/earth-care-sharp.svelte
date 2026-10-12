<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rfii-0k4v"/><path class="l9t_zy80f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:earth-care-sharp" {...props}></Icon>
<style>
:global(.l9t_zy80f) {
  d: path("M12 3a12.75 12.75 0 0 0 0 12M6 9a12.75 12.75 0 0 0 12 0M3 13.5c.5 4.5 3.5 6.75 7.5 6.75M21 13.5c-.5 4.5-3.5 6.75-7.5 6.75");
}

:global(.rfii-0k4v) {
  cx: 12px;
  cy: 9px;
  r: 6px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="si0wi76vy"/><path class="lq67wmbaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mvp-award" {...props}></Icon>
<style>
:global(.lq67wmbaz) {
  d: path("M7 5.5H4v2A3.5 3.5 0 0 0 7.5 11M17 5.5h3v2a3.5 3.5 0 0 1-3.5 3.5M12 14v6m-3.5 0h7");
}

:global(.si0wi76vy) {
  d: path("M7 4h10v5A5 5 0 0 1 7 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

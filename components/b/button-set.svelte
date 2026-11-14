<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f5i706bnm"/><path class="u_gn9nbgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:button-set" {...props}></Icon>
<style>
:global(.f5i706bnm) {
  d: path("M4 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Z");
}

:global(.u_gn9nbgx) {
  d: path("M12 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM8.5 8.5h.01m2.99 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

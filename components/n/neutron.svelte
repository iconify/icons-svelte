<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="od7ufjb-t"/><path class="o4chtcbfi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:neutron" {...props}></Icon>
<style>
:global(.o4chtcbfi) {
  d: path("M4.75 19.25a10.25 4.5-45 1 1 14.5-14.5a10.25 4.5-45 1 1-14.5 14.5ZM12 12h.01");
}

:global(.od7ufjb-t) {
  d: path("M4.75 4.75a10.25 4.5 45 1 1 14.5 14.5a10.25 4.5 45 1 1-14.5-14.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l4xrjbc6o"/><path class="loe9cmdpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aye-aye" {...props}></Icon>
<style>
:global(.l4xrjbc6o) {
  d: path("M7.5 14a4.5 5.5 0 1 0 9 0a4.5 5.5 0 1 0-9 0ZM2.25 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm13.5 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-5.75 8h.01m3.99 0h.01");
}

:global(.loe9cmdpg) {
  d: path("M15.75 17L19 18.5l2.5-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

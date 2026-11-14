<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wpullwedc"/><path class="r1rm97bfa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hand-mirror" {...props}></Icon>
<style>
:global(.r1rm97bfa) {
  d: path("m7.636 13.389l2.475 2.475l-4.42 4.419l-2.474-2.474ZM11 10l3.5-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wpullwedc) {
  d: path("M7.5 9.5a6.5 7.5 0 1 0 13 0a6.5 7.5 0 1 0-13 0Z");
}

</style>

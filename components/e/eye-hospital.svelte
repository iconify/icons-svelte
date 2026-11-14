<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pjlklyebz"/><path class="j6t8d2brw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eye-hospital" {...props}></Icon>
<style>
:global(.j6t8d2brw) {
  d: path("M5.5 15.75c2.5-4.25 10.5-4.25 13 0C16 20 8 20 5.5 15.75Zm6.5 0h.01");
}

:global(.pjlklyebz) {
  d: path("M2.5 21.5V9H7V2.5h10V9h4.5v12.5ZM12 5.25v4m-2-2h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

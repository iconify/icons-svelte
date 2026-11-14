<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8y1jkbzs"/><path class="d___vbc1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mass-vs-weight" {...props}></Icon>
<style>
:global(.d___vbc1j) {
  d: path("M4 9.5h4l1.5 10h-7ZM16.25 5v14.5m-3 0h6M12.5 7H20m-7.5 0v3.5m-1.5 0a1.5 1.5 0 0 0 3 0ZM20 7v3.5m-1.5 0a1.5 1.5 0 0 0 3 0Z");
}

:global(.h8y1jkbzs) {
  d: path("M3.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

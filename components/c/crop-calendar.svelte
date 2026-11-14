<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="js0w5s5qh"/><path class="hcf6lwbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crop-calendar" {...props}></Icon>
<style>
:global(.hcf6lwbzq) {
  d: path("M12 16.25c0-1.52-1.12-2.43-3-2.5c.07 1.65 1.2 2.55 3 2.5Zm0-.75c0-1.9 1.13-3.25 3-3.25c-.07 1.8-1.2 3.15-3 3.25Z");
}

:global(.js0w5s5qh) {
  d: path("M3.5 4.5h17v16h-17ZM8 3v3.5M16 3v3.5M3.5 9h17M12 18.5v-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

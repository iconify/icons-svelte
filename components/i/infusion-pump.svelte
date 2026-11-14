<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x4pknq47x"/><path class="soauomb7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:infusion-pump" {...props}></Icon>
<style>
:global(.soauomb7m) {
  d: path("M15 10.5h5v2.25h-5Zm-8.5 2c0 2.5 3 3 7 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x4pknq47x) {
  d: path("M12 2.5v17m-4 2h8m-4-2v2M13.5 9h8v6.5h-8Zm-10-4.5h6v8h-6Zm3-2H12m-5.5 0v2");
}

</style>

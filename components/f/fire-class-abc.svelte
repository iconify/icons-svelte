<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q2li-tkqb"/><path class="g29pwpzzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fire-class-abc" {...props}></Icon>
<style>
:global(.g29pwpzzq) {
  d: path("M12 6.5C14.5 9 16.5 11 16.5 14a4.5 4.5 0 0 1-9 0c0-2 1-3.5 2.25-4.5c.25 1.5 1 2.5 2 2.75c-.5-2.25-.5-4.25.25-5.75Z");
}

:global(.q2li-tkqb) {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2v15a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

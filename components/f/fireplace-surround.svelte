<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="legud0bli"/><path class="p-lw3nbyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fireplace-surround" {...props}></Icon>
<style>
:global(.legud0bli) {
  d: path("M2.5 4h19m-17 0v16.5M19.5 4v16.5m-17 0h19M8 20.5V12a4 4 0 0 1 8 0v8.5");
}

:global(.p-lw3nbyg) {
  d: path("M12 12.25c1 1 1.5 2.5 1.5 4a1.5 1.5 0 0 1-3 0c0-1.5.5-3 1.5-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

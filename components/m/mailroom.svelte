<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9_bc8bri"/><path class="xciiyzblg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mailroom" {...props}></Icon>
<style>
:global(.p9_bc8bri) {
  d: path("M2.5 2.5h19v19h-19Zm9.5 0v19M2.5 12h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xciiyzblg) {
  d: path("M12 2.5L16.75 7l4.75-4.5");
}

</style>

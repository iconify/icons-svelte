<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jwo50wymy"/><path class="lewvbubjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:party-hat-sharp" {...props}></Icon>
<style>
:global(.jwo50wymy) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.39 6.92l5.22 12.16l.39.92H6l.39-.92l5.22-12.16L12 6z");
}

:global(.lewvbubjo) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01M10 16.5h.01m3.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

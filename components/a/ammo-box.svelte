<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qnakscces"/><path class="zs8tautir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ammo-box" {...props}></Icon>
<style>
:global(.qnakscces) {
  d: path("M2.5 4.5h19v4h-19Zm1 4V18A1.5 1.5 0 0 0 5 19.5h14a1.5 1.5 0 0 0 1.5-1.5V8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zs8tautir) {
  d: path("M10.5 8.5v3a1.5 1.5 0 0 0 3 0v-3M7 8.5v11m10-11v11");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jeoaurmiu"/><path class="is4tjv2yr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:centre-line" {...props}></Icon>
<style>
:global(.is4tjv2yr) {
  d: path("M2.5 8.5h3v7h-3m19-7h-3v7h3M12 12h.01");
}

:global(.jeoaurmiu) {
  d: path("M2.5 4.5h19v15h-19Zm9.5 0v15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

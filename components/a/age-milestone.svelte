<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2snh5b8j"/><path class="zfkk39bhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:age-milestone" {...props}></Icon>
<style>
:global(.o2snh5b8j) {
  d: path("M12.771 21H4.5L12 6l3.309 6.619");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zfkk39bhh) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-.5 7h5M7 16h3m7.75-2l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>

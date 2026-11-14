<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u1f7p0hhg"/><path class="s9o4jp5_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crossbuck-sign" {...props}></Icon>
<style>
:global(.s9o4jp5_a) {
  d: path("m4.586 11.61l13.107-9.177l1.721 2.457l-13.107 9.177ZM12 8.25V21.5");
}

:global(.u1f7p0hhg) {
  d: path("m6.307 2.433l13.107 9.177l-1.721 2.457L4.586 4.89Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

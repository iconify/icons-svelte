<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3d7t6btp"/><path class="yugbdabaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newsletter-issue-x" {...props}></Icon>
<style>
:global(.l3d7t6btp) {
  d: path("M12.6 21.5H3.5v-19h15v11.1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yugbdabaj) {
  d: path("m7 6l4 3l4-3m-8 6.5h7.6m-7.6 4h4m4.5-1l5 5m0-5l-5 5");
}

</style>

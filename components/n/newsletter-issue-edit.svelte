<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z28_zlb5g"/><path class="gu6l14bre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newsletter-issue-edit" {...props}></Icon>
<style>
:global(.gu6l14bre) {
  d: path("m7 6l4 3l4-3m-8 6.5h8m-8 4h4m4 5V19l4.5-4.5A1.75 1.75 0 0 1 22 17l-4.5 4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z28_zlb5g) {
  d: path("M12.2 21.5H3.5v-19h15v9.3");
}

</style>

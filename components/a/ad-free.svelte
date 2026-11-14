<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fodytqh7n"/><path class="eduusueal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ad-free" {...props}></Icon>
<style>
:global(.eduusueal) {
  d: path("M10.6 14.5H6V9.9m8-.4h4m-14.5-6l17 17");
}

:global(.fodytqh7n) {
  d: path("M7.9 4h13.6v13.6m-7.4.4H2.5V6.4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

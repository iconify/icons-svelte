<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wojy1qvcu"/><path class="ga_sosbfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:demo-request" {...props}></Icon>
<style>
:global(.ga_sosbfj) {
  d: path("m9.75 6.5l5.5 3.5l-5.5 3.5ZM18 15v6m-3-3h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wojy1qvcu) {
  d: path("M12.2 16.5H2.5v-13h19v11.7M12 16.5V21m-2.25 0h4.5");
}

</style>

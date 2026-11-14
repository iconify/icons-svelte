<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp6xhvbxo"/><path class="izmkdabrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:api-error" {...props}></Icon>
<style>
:global(.hp6xhvbxo) {
  d: path("M13.255 17.156L10 19l-7.5-4.25v-8.5L10 2l7.5 4.25v7.28");
}

:global(.izmkdabrt) {
  d: path("M2.5 6.25L10 10.5l7.5-4.25M10 10.5V19m5.5-3.5l6 6m0-6l-6 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jss4ote_a"/><path class="e3grvl8la"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:freezer-warehouse" {...props}></Icon>
<style>
:global(.e3grvl8la) {
  d: path("M8 21v-6.5h8V21m-8-3.25h8");
}

:global(.jss4ote_a) {
  d: path("M2.5 21v-7.5l9.5-3.25l9.5 3.25V21ZM12 2.5v5M9.75 3.75l4.5 2.5m-4.5 0l4.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

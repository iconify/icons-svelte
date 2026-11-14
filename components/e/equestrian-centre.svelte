<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ods-c5btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:equestrian-centre" {...props}></Icon>
<style>
:global(.ods-c5btg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.5 21.5c1-6.5.5-13-3.5-17l-.5-2l-2 2c-3 1.5-6 5.5-8 9.5c-.5 1.5 1 3 2.5 2.5l4-2c1 1.5 1.5 4 .5 7ZM13 9h.01");
}

</style>

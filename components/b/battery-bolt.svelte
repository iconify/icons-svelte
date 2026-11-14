<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="evat56uiq"/><path class="db2cyynzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-bolt" {...props}></Icon>
<style>
:global(.db2cyynzf) {
  d: path("m13 8l-2.75 5h3.5L11 18");
}

:global(.evat56uiq) {
  d: path("M6.5 4.75h11V21.5h-11Zm3.5-2h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

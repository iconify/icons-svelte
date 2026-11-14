<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v8mh_xuqv"/><path class="en6lazoab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:boxer-jab" {...props}></Icon>
<style>
:global(.en6lazoab) {
  d: path("M9.5 12.5H14a3 3 0 0 1 3 3V19M2.5 6h4m-4 12h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v8mh_xuqv) {
  d: path("M12.5 5h6a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-6a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3Zm-7 4h4v6h-4Z");
}

</style>

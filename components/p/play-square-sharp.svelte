<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs7l5kcfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:play-square-sharp" {...props}></Icon>
<style>
:global(.bs7l5kcfr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.88 5.05l9.24 5.65l2.13 1.3l-2.13 1.3l-9.24 5.65l-2.13 1.3V3.75z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szztljbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dive-torch" {...props}></Icon>
<style>
:global(.szztljbvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5H13v5H2.5Zm10.5 0l3-2v9l-3-2ZM18.5 7L21 5.5M18.5 12h3m-3 5l2.5 1.5");
}

</style>

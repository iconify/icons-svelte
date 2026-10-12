<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhqn-kzec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:boot-sharp" {...props}></Icon>
<style>
:global(.zhqn-kzec) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 2.75h7.25v9.75l5.15 1.9l2.599 1.056l.251 2.794H4.5Zm3.75 3.5h3.5m-3.5 3h3.5m-7.25 9h15.25v3H4.5z");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":237};
const content = `<path class="sq47ywbfl"/><path class="sfzqwtbnw"/><path class="fz0svbdar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:dreamfactory" {...props}></Icon>
<style>
:global(.fz0svbdar) {
  d: path("M256 237H43.396L0 212.443h213.277L256 237z");
  fill: var(--svg-color--b83c23, #B83C23);
}

:global(.sfzqwtbnw) {
  d: path("M213.277.175L256 25.74V237l-2.427-.58l-39.283-22.377l-1.013-1.6V.175z");
  fill: var(--svg-color--f78d2a, #F78D2A);
}

:global(.sq47ywbfl) {
  d: path("M102.602 165.683C77.852 133.2 92.582 67.731 155.417 72.5c-74.78-86.207-171.265 63.165-52.815 93.183");
  fill: var(--svg-color--b83c23, #B83C23);
}

</style>

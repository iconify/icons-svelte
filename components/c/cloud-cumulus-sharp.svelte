<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgcg_phct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cloud-cumulus-sharp" {...props}></Icon>
<style>
:global(.bgcg_phct) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 19.5a3.5 3.5 0 1 1 .99-6.86a5.5 5.5 0 1 1 9.02 0a3.5 3.5 0 1 1 .99 6.86Z");
}

</style>

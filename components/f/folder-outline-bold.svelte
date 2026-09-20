<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr36_-kty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-outline-bold" {...props}></Icon>
<style>
:global(.wr36_-kty) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M20 7v13H4V4h5l3 3h4");
}

</style>

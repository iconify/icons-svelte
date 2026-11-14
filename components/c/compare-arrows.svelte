<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="modt-kbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:compare-arrows" {...props}></Icon>
<style>
:global(.modt-kbti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v18M3 8h6M6 5l3 3l-3 3m15 5h-6m3-3l-3 3l3 3");
}

</style>

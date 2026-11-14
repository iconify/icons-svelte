<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcsi97yaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:paragraph-mark" {...props}></Icon>
<style>
:global(.pcsi97yaz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 4v8h-3a4 4 0 0 1 0-8Zm0 0h5m-5 0v16m4-16v16");
}

</style>

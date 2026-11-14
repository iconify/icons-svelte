<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arqmtsnrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flask-empty" {...props}></Icon>
<style>
:global(.arqmtsnrl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v6.5l-5 9.75A1.5 1.5 0 0 0 5.75 21h12.5a1.5 1.5 0 0 0 1.25-1.75l-5-9.75V3M8 3h8");
}

</style>

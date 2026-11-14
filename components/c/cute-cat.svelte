<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c72its8uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cute-cat" {...props}></Icon>
<style>
:global(.c72its8uf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 9l.5-5.5l4.5 3a8 8 0 0 1 4 0l4.5-3L19 9A8 8 0 1 1 5 9m4 3h.01M15 12h.01M12 15h.01");
}

</style>

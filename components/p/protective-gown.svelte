<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6rj1nb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:protective-gown" {...props}></Icon>
<style>
:global(.q6rj1nb6v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 3l3 3l3-3l4 3l-1.5 3.5V21h-11V9.5L5 6Zm3 3v15");
}

</style>

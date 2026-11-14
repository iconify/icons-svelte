<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgr6vj-lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:focus-point" {...props}></Icon>
<style>
:global(.rgr6vj-lt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m6.5 0h.01M12 2.5v3m0 13v3M2.5 12h3m13 0h3");
}

</style>

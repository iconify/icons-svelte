<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czhpw5tqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:co-presence" {...props}></Icon>
<style>
:global(.czhpw5tqk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 18.5a4 4 0 0 1 8 0m3 0a4 4 0 0 1 8 0m-19 0h19");
}

</style>

<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kblyrccku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:covalent-bond" {...props}></Icon>
<style>
:global(.kblyrccku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0m12 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-2-1.5h.01m-.01 3h.01M6 12h.01M18 12h.01");
}

</style>

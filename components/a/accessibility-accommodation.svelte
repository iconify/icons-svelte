<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sncbxzbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:accessibility-accommodation" {...props}></Icon>
<style>
:global(.sncbxzbgc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21v-1l10-7h9v8Zm10-8v8m-10-7l10-7M5 12.25v2.5m5-6v2.5");
}

</style>

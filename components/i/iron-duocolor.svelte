<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i-cfj8p9g"/><path class="ak85j4bex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:iron-duocolor" {...props}></Icon>
<style>
:global(.ak85j4bex) {
  d: path("M21 11v5a2 2 0 0 1-2 2H4c-.369 0-.369-.631 0-1l5-5c.64-.64 1.36-1 2-1z");
}

:global(.i-cfj8p9g) {
  stroke-opacity: 0.4;
  d: path("M21 11V8a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

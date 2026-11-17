<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q5bjc-b2i"/><path class="nyad9_jml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-badge-up-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.nyad9_jml) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 15v4c0 .369-.631.369-1 0l-5-5a1.414 1.414 0 0 0-2 0l-5 5c-.369.369-1 .369-1 0v-8l6-6a1.414 1.414 0 0 1 2 0l6 6z");
}

:global(.q5bjc-b2i) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 19c0 .369-.631.369-1 0l-5-5a1.415 1.415 0 0 0-2 0l-5 5c-.369.369-1 .369-1 0v-8l6-6a1.415 1.415 0 0 1 2 0l6 6Z");
}

</style>

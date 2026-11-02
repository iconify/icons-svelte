<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vebsodbpg"/><path class="s7e_ee__v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-download-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s7e_ee__v) {
  d: path("m5 6l1-2h12l2 4v12H4V8zM4 8h16");
}

:global(.vebsodbpg) {
  stroke-opacity: 0.4;
  d: path("m9 14l3 3l3-3m-3 3v-6");
}

</style>

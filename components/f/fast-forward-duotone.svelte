<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m4mvh9tea"/><path class="jp41_8btc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fast-forward-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.jp41_8btc) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5.256 7.204l6 3.5a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 3 15.5v-7a1.5 1.5 0 0 1 2.256-1.296m9 0l6 3.5a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 12 15.5v-7a1.5 1.5 0 0 1 2.256-1.296");
}

:global(.m4mvh9tea) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11.256 10.704a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 3 15.5v-7a1.5 1.5 0 0 1 2.256-1.296Zm9 0a1.5 1.5 0 0 1 0 2.592l-6 3.5A1.5 1.5 0 0 1 12 15.5v-7a1.5 1.5 0 0 1 2.256-1.296Z");
}

</style>
